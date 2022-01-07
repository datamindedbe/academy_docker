# Data Minded Academy - Containerization with Docker
## Exercise 4 - Write the Dockerfile of a simple Python

In this exercise, you are tasked to containerize a simple Streamlit app tracking the Uber rides in New York City. The application can be seen running live for demonstration purposes [at this address](https://share.streamlit.io/streamlit/demo-uber-nyc-pickups/). The source code of the application is available in the subfolder `app` of the `exercise_4` folder.

In this exercise, you are asked to containerized this simple application. To do so, refer to the application's `README.md`. 

1. Write the Dockerfile that will define your Docker image, build, and run it to make sure everything is working as expected.

2. Try to reflect on how to optimize your Dockerfile in terms of layers and caching capability. Make sure the dependencies installation isn't re-run at build tim everytime something change in `streamlit_app.py`.
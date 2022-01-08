# Data Minded Academy - Containerization with Docker
## Exercise 4 - Write the Dockerfile of a simple Spring (Java) application

In this exercise, you are tasked to containerize a simple Spring (Java) application. The source code of the application is available in the subfolder `app` of the `exercise_5` folder. The instructions about how to setup the application should be straightforward and are written in the app's `README.md`.

1. Write the Dockerfile that will define your Docker image, build, and run it to make sure everything is working as expected. Tips: use the [`openjdk:_tag_` image](https://hub.docker.com/_/openjdk?tab=description) as a base image. You’ve completed the exercise when you see a ‘Success’ message in your browser.

2. Try to reflect on how to optimize your Dockerfile in terms of layers and caching capability. Is there something you can improve in this regard considering the required build process ?

3. [Create an account in DockerHub](https://hub.docker.com/) and push the Streamlit app image to it. Delete the image you have locally and try to pull it from your Dockerhub account.
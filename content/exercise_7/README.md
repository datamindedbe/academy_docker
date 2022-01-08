1. Create an account on [Heroku](https://www.heroku.com/)

2. Login to Heroku: 
```
heroku login -i
```

3. Create an Heroku app from the terminal:
```
heroku create <your-app-name>
```

4. Login to Heroku's Container Registry:
```
heroku container:login
```

5. Push the Streamlit image to the Heroku registry:
```
cd /workspace/exercise_7/app
heroku container:push --app <your-heroku-app-name> web 
```

6. Release the app: 
```
heroku container:release --app <your-heroku-app-name> web
```


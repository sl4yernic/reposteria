This is a multi container app.

This app uses 3 different docker containers all running nginx: the web, api and an reverse proxy container.

To run the app download the repo, cd to the redirect directory and run `docker compose up -d` since we are using docker-compose.yaml you do not need to manually build each app.

This app uses port 8080 for the web app, change the port in case other apps in your environment are using it.

Access the root app by opening your browser and typing `localhost:8088/`

Access the API by typing `localhost:8088/api`

The nginx app is in charge of redirecting traffic by using a reverse proxy, defined in the nginx.conf (proxy pass).

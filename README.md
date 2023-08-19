# Dockerized Fullstack CRUD App 
The app is uses the SERN stack and is a simple CRUD application in the theme of volleyball teams
- MySQL
- Express
- React
- Node.js
- Docker + Docker Compose

# Building the app
Since the app is dockerized, you can simply utilize docker compose to build the app
- `cd` to this repository
- Build with: `docker compose build`

# Running the app
- Spin up the docker compose: `docker compose up`
- The app runs on `http://localhost:80`
![image](https://github.com/ausbennett/docker-fullstack-volleyball/assets/61357467/20025ebd-65f7-457b-8cb7-5c2d714c0579)
![image](https://github.com/ausbennett/docker-fullstack-volleyball/assets/61357467/e6d628f4-5925-4a9d-9ad5-a517766e8b15)


# Stopping the app
Docker compose will handle stopping the application
- Quit process with: `CTRL+C`
- Shutdown with: `docker compose down`

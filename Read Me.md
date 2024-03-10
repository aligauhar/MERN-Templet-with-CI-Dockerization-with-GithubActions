# Instructions
1. clone repo
2. cd to frontend run npm i
3. cd to backend run npm i
4. follow backend/config/config_sample.env
5. follow frontend/config/config_sample.env
6. npm run dev for fronend and backend

or 

1. pull the dockers repo from aliguahar/frontend and aliguahar/backend
2. run frontend on port 8080 and backend on 8000 <- ports config are necessary to integrate frontend with backend


# When Deploying
1. Set the dockers variables in secrets
2. Customize Dockerfile if any changes
3. Customize Vercel gitActions for your vercel repo
4. push it in you repo

# *****What will you get here?
# Backend and Database
This is a basic tamplet that make the initial mern stack website building setup easy
It includes JSON API for handling frontend contend
Mongoose DataBase integration with Atlas
Express bakend with controller, routes, Models and errorHandlers with simple form implementation

# Frontend
Vite-React frontend with components and api callind for connecting the backend through axon

# CI/CD
Automatic Dockerization with github actions
Automatic Web Hosting on  Vercel with Github Action
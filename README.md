# Templates Expressjs
 This is basic templates project expressjs for backend
# Install:
    npm install
# Setting .env:   
    change your environments in .env
    make new file .env.production if you want to deploy your project
# usage:
    npm run dev ( use .env.production)
    npm start ( use .env)
# Structure:
    ./src/controller/ -> Manager API
    ./src/middleware/ -> Manager middleware
    ./src/models/ -> Manager mongoose Schema
    ./src/routers/routes -> routes API
    ./src/ -> Manager public html
    ./scratch -> manager localstorage if you use localstorage
# Dependency
    Cors,
    Axios,
    dotenv,
    jsonwebtoken,
    nodemon,
    body-parser,
    socket.io,
    node-localstorage,
    mongodb,
    mongoose

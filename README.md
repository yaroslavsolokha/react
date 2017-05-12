### Docker for React

Environment for react development.

#### Install Frontend
##### 1. cd Projects/react
##### 2. docker-compose build
##### 3. docker-compose up
##### 4. docker exec -it frontend /bin/sh
##### 5. create-react-app frontend
##### 6. cd frontend
##### 7. npm start
##### 8. Happy hacking!

#### Install Backend
##### 1. cd Projects/react
##### 2. docker-compose build
##### 3. docker-compose up
##### 4. docker exec -it backend /bin/sh
##### 5. express backend
##### 6. cd backend
##### 7. npm install
##### 8. npm install --save nodemon
##### 9. npm install --save babel-preset-es2015
##### 10. npm install --save babel-cli
##### 11. npm install --save sequelize
##### 12. npm install --save mysql
##### 13. npm install --save sequelize-cli
##### 14. npm start
##### 15. Happy hacking!

#### Start
```
$ cd Projects/react
$ docker-compose up
$ docker exec -it backend /bin/sh
$ docker exec -it frontend /bin/sh
$ cd backend
$ npm start
$ cd frontend
$ npm start
```
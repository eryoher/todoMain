To run the project you need to do the following steps

* [CLONING PROJECT]

* git clone --recursive https://github.com/eryoher/todoMain.git 

* [INITIALIZE SUBMODULES]

**Service Tasks**
* cd tasksApi
* yarn install o npm install
* import the db with the query todoList_tasks.sql
* add the local database configuration to the file server/datasource.json
* if you want to change the port it is done in the following file server/config.json
* yarn start o nmp run start


**Service Users**
* cd usersApi
* yarn install o npm install
* import the db with the query todoList_users.sql
* add the local database configuration to the file server/datasource.json
* if you want to change the port it is done in the following file server/config.json
* yarn start o nmp run start


**App**
* cd todoListApp
* yarn install o npm install
* update the .env file with the apis configuration
* yarn start o nmp run start

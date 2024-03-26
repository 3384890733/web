## Folder
- flash-api back-end server start
- flash-vue-admin
- flash-core


## Guide
- clone project
- create database：web-flash
     ```sql
        CREATE DATABASE IF NOT EXISTS webflash DEFAULT CHARSET utf8 COLLATE utf8_general_ci; 
        CREATE USER 'webflash'@'%' IDENTIFIED BY 'webflash190602@ABC';
        GRANT ALL privileges ON webflash.* TO 'webflash'@'%';
        flush privileges;
     ```
- run flash-api，access http://localhost:8082/swagger-ui.html
- enter folder: flash-vue-admin
    - npm install
    - npm run dev
    - http://localhost:9528 ,account:admin    

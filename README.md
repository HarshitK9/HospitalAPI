# Hospital_API
travelled-app

** Folder Structure and Technologies used **
|
---------->Root_Folder
                |
                 --------models-----> MongoDB
                |
                 --------> controllers---> all functionality of backend APIs
                |
                 ---------> routers------> setup different routes
                 |
                  --------->config -------> jwt setup [middleware]
                 |
                  ----------> index.js -----> triggering point of server-----> node express-server
                 |
                  ----------> server.js-----> all setups of app [ requiring all related frameworks , set-up DB connections, method for firing up server etc. ]
  
  
  **Installation in loclals**
     1. first you have to create your own environments variables
     2. pass commands---
                        a. npm install
                        b. node index.js
          in your powershel's terminal

`docker build -t [APPLICATION] [DIRECTORY]`  
e.g. `docker build -t mustakim/jenkins .`  

`docker run -d -p [PORT:PORT] --name [APP_NAME] [APPLICATION]`  
e.g. `docker run -d -p 8080:8080 --name jenkins mustakim/jenkins`

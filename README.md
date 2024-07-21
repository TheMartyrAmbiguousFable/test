
# Chat Now

## Installation Instructions

### 1. Install MongoDB

- **Step 1.**  https://www.mongodb.com/try/download/community Download the installer from here 

- **Step 2.**  On the Choose setup type screen select *complete* and on the service configuration screen select *Run Service as Network Service User*

**IF YOU ARE UNABLE TO INSTALL MONGO DB REACH OUT TO a1879980@adelaide.edu.au for connection URL**
### 2. Clone the Repository

Tested on Nodejs 18.17.1 , NPM 9.6.7

Clone the repository using Git:

```bash
git clone https://github.com/harshu4/Backdoored-Chat.git
cd Backdoored-Chat
```

Start the Backend: 
```bash
npm install --loglevel=error #if this throws error try npm install --legacy-peer-deps

npm start  
```

Start the Frontend:
```bash
cd <Projectdir>/frontend 
npm install --loglevel=error  #if this throws error try npm install --legacy-peer-deps
npm start
```

Further Instructions 

File : ips.json 

Update the file ips.json with key set as servername and value as their IP 


File : .env 

Set env config here 

Mongo_URI : Connect to mongo DB URL

JWT_SECRET : Security Parameter for JWT can be any string

SERVER_NAME :  Name of your own server ex : s10

EXTERNAL_WS_PORT : The port that all other servers are running on ex : 5555 

PORT : The port that you want to run your server on ex : 5555


*The .env has been explosed intenionally and is not a part of the backdoor*

# Tested
This program has been tested to work with 

Group 1 
Group 4
Group 3
Group 11
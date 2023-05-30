# Getting-Started-With-NODE-JS

### NODE JS WITH FLUTTER

Nodejs is basically built to communicate with server which initially was not possible in JS, as JS was restricted to client side only.

### INITIALIZATION

 Anyone can easily Download it from [https://nodejs.org/en](https://nodejs.org/en)

In your flutter project make a folder at root named as server, and initialize your node there, use terminal and in server directory run the initialization command

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/npminit.png" width="20%">

### npm stands for Node Package Manager

after running the command, a package.json file will automatically built in server folder

- Creating **Index.js** in server folder, you can change the name of **index.js** but you should change the ####index.js in **package.json** file first.

  - You can try out a simple script to check if it is working fine or not

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/console.png" width="40%">

  - Run the script by running a command in server

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/run.png" width="25%">

- Install the dependencies that you will need in the process

  - You can check out for dependencies at [https://www.npmjs.com/](https://www.npmjs.com/)

  - The first few dependencies that you need to download are:

    - http
    - express
    - mongoose


  - You can add these dependencies simply by running simple command in server terminal

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/depend.png" width="40%">

**Connection Building**

- the below code is written to check if server is working or not in **Index.js**

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/Connection.png" width="50%">

- That would be the output we get on running **index.js**

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/OUTPUT.png" width="40%">

- Installing another dependency i,e dev dependency that will help us to break the loop , when you will run the above code it will kept running and you have to terminate the whole process, so to avoid that we will be using **NODEMON DEPENDENCY**.

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/nodemon.png" width="40%">

  - Now to activate the nodemon, you have to write a script in **package.json**

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/script.png" width="40%">

**Creating API**

- Now we are creating our First API

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/API.png" width="50%">

- Now go to your server terminal and run the command

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/run%20dev.png">

- Now your server is running. Go to your browser and write the below URL.

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/localhost.png">

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/Cannot.png">

- As you can see it is giving \*Cannot Get /\* msg this is because we have not given the correct path that will show us the JSON quoted msg, check out the above API code, you will get it whats the right path to get result.

 -------------------------------------------------------------------------------------------------------


- Adding 2 Get Requests at 2 paths

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/2%20Get.png">

- Our Default Path will look like this removing the Cannot Get /

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/3000.png">

- The /helloworld path

<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/hello%20world.png">

### ROUTE BUILDING

- We will do routing now to manage multiple requests

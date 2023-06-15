# Getting-Started-With-NODE-JS

### INSTALLING THE DEPENDENCIES

- Install the dependencies that you will need in the process

  - You can check out for dependencies at [https://www.npmjs.com/](https://www.npmjs.com/)

  - The first few dependencies that you need to download are :

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

--------------------------------------------------------------------------------------------------

### INDEX.JS
<img src = "https://github.com/MirzaRizwan02/Getting-Started-With-NODE-JS/blob/main/Guide/Indexjs.png" width="50%">

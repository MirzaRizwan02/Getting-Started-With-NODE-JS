# Getting-Started-With-NODE-JS

**NODE JS WITH FLUTTER**

Nodejs is basically built to communicate with server which initially was not possible in JS, as JS was restricted to client side only.

**INITIALIZATION**

 Anyone can easily Download it from [https://nodejs.org/en](https://nodejs.org/en)

In your flutter project make a folder at root named as server, and initialize your node there, use terminal and in server directory run the initialization command

![](RackMultipart20230528-1-eeua5b_html_8f282b385528d3.png)
**npm** stands for Node Package Manager

after running the command, a package.json file will automatically built in server folder

- Creating Index.js in server folder, you can change the name of index.js but you should change the index.js in package.json file first.

  - You can try out a simple script to check if it`s working fine or not

![](RackMultipart20230528-1-eeua5b_html_4289984fd8fe086d.png)

  - Run the script by running a command in server

![](RackMultipart20230528-1-eeua5b_html_9c7befd0031f339a.png)

- Install the dependencies that you will need in the process

  - You can check out for dependencies at [https://www.npmjs.com/](https://www.npmjs.com/)

  - The first few dependencies that you need to download are:

    - http
    - express
    - mongoose


  - You can add these dependencies simply by running simple command in server terminal

![](RackMultipart20230528-1-eeua5b_html_68740e2fe02f1c68.png)

**Connection Building**

- the below code is written to check if server is working or not in Index.js

![](RackMultipart20230528-1-eeua5b_html_1bf24615ec705e22.png)

- That would be the output we get on running index.js

![](RackMultipart20230528-1-eeua5b_html_3fd8e86f118cda54.png)

- Installing another dependency i,e dev dependency that will help us to break the loop , when you will run the above code it will kept running and you have to terminate the whole process, so to avoid that we will be using **NODEMON DEPENDENCY**.

![](RackMultipart20230528-1-eeua5b_html_6eec684f0865188.png)

  - Now to activate the nodemon, you have to write a script in package.json

![](RackMultipart20230528-1-eeua5b_html_6e2af4b790123607.png)

**Creating API**

- Now we are creating our First API

![](RackMultipart20230528-1-eeua5b_html_b1937be297bc9fcc.png)

- Now go to your server terminal and run the command

![](RackMultipart20230528-1-eeua5b_html_ad6403e1971c00cf.png)

- Now your server is running. Go to your browser and write the below URL.

![](RackMultipart20230528-1-eeua5b_html_3b40dfe68a819dd5.png)

![](RackMultipart20230528-1-eeua5b_html_bb3955196fd3fe8b.png)

- As you can see it is giving \*Cannot Get /\* msg this is because we have not given the correct path that will show us the JSON quoted msg, check out the above API code, you will get it whats the right path to get result.

 -------------------------------------------------------------------------------------------------------


- Adding 2 Get Requests at 2 paths

![](RackMultipart20230528-1-eeua5b_html_6103a0a5d67232dd.png)

- Our Default Path will look like this removing the Cannot Get /

![](RackMultipart20230528-1-eeua5b_html_3f388257ce70065b.png)

- The /helloworld path

![](RackMultipart20230528-1-eeua5b_html_4285ae45e58dfbe0.png)

**ROUTE BUILDING**

- We will do routing now for better understanding, which will help us to navigate easily btw the screens

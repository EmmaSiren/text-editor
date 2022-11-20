# <text-editor>
# **Text Editor**

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=Webpack&logoColor=white)
![Babel](https://img.shields.io/badge/Babel-F9DC3E?style=for-the-badge&logo=babel&logoColor=white)


## **Description**
Using the provided starter code, I was able to complete building a full stack application text editor. The challenge with creating a PWA comes in knowing how to register a custom service worker that will help inject a manifest file as well as cache necessary assets for offline function. It was very important to make sure that each package.json file had the necessary dependencies for the specific folder it was in. That meant creating three separate package.json files for the client, server, and root folders. I had to ensure I understood what the plugins that I was adding to the webpack.configure file were in order to fill them out correctly so that the app functioned properly. This was especially important for the service worker. 

The text editor will take user input, save it to an indexDb on the client side, serve it up when the user returns to the page after closing it out, and be downloadable as a PWA with cached assets. 

 ## **Installation & Usage**

Please visit https://damp-waters-97002.herokuapp.com/ to view the deployed application on Heroku. Below you will find a screenshot of the application. 

![Screenshot](/app-scrnsht-for-readme.jpg)

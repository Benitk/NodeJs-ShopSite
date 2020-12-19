# NodeJs-ShopSite


## This project includes:
* Parsing Requests & Sending Responses using Express.js
* Registration, Login management with user authentication and authorization
* Integration with mongodb by using moongose
* Rendering HTML Dynamically (on the Server) using ejs
* Using the Model-View-Controller (MVC) Pattern
* Sessions & Cookies

## Installation:
clone this repo into local folder.

**With Docker**
* create .env file and write ``` MONGODB_CONTAINER_URI=mongodb://mongo:27017/shop ```
* open terminal in repo folder and write ``` docker-compose build ```  ``` docker-compose up ```

**With 3rd party mongodb service**
* create .env file and write ``` MONGODB_URI=YourAPIKey ```
* open terminal in repo folder and write ``` npm install ```  ``` npm start ```

now open your browser at localhost:3000 and have fun


example pics:

![](https://github.com/Benitk/NodeJs-ShopSite/blob/master/pics/products.png)

![](https://github.com/Benitk/NodeJs-ShopSite/blob/master/pics/add%20product.png)

### this project is built by following Maximilian Schwarzmüller nodejs course ![link](https://www.udemy.com/course/nodejs-the-complete-guide)






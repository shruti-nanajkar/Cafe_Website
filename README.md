Problem Statement:
- Create an e-commerce website hich supports CRUD operations. 
- Project should use angular2+, angular-cli and any libraries; SCSS and any CSS frameworks you require.

Requirements:
- User should be able to login using some apikey or username/password login.
- User should be to do a search.
- User should be able to sort the results.
- User should be able to create a record.
- User should be able to see a detailed view of the record.
- User should be able to edit a record.
- User should be able to delete a record.
- User should be able to log out of the application.
- User should be able to bookmark search, create, edit, view operation URLs.

Implementation:
- The project uses Angular4 syntax for implementing the Presentation Application.
- Each section of the application is divided into components with its specific funtionality.
- When the application is launched, Home page is displayed to the user. 
- The user can learn more about the Website features and navigate to About Us page.
- The User can also explore Cafes in the vicinity or at specific location.
- User can explore various products from the Menu page and also get more detailed information about each of those.
- The product can directly be added to the User's cart to proceed ahead with the checkout.
- If the user is not already signed in, he will be prompted to do so. Otherwise he can simply proceed ahead with payment.
- The user also has the flexibility to update i.e add/update items from the cart.
- User can also try his luck in earning Exciting Offers and Discounts with the Spin-The-Wheel game.
- Upon successful checkout and payment, he will be displayed a confirmation receipt of his Order.

Instructions to run the project:
- NodeJs, npm Angular CLI and mongodb shell client is required. If you don't have it please install that first.
- Clone the URL or download the project zip from the github.
- Run 'npm install' inside each of the projectUI and projectAPI folders for installing npm dependencies.
- Once all the installations are complete, go to the directory where mongodb client is installed. 
- Traverse to its \bin folder and copy the path. The path should look similar to "C:\Program Files\MongoDB\Server\3.6\bin" for you local machine.
- Create a data\db folder under C:\ or Copy the data\db folder from the extracted project zip and and place it under C:.
- This copied data\db folder contains pre-loaded Product data along with other User Details collections.

Now follow the steps below to run the application: (Please maintain the sequence to avoid any errors)
- Open 2 Command Prompts using Administrator Mode. Type "cd C:\Program Files\MongoDB\Server\3.6\bin" in each of those shells.
- In one of the shell, first run the "mongod". You should see .....waiting for connections on port 27017 in the logs.
- Now in the second shell, run "mongo". You should see ...connecting to: mongodb://127.0.0.1:27017 .... [initandlisten] in the logs.
- This will access mongodb data from data\db under C:.
- Open the Git Bash inside projectAPI and run "npm start". 
- This will allow Angular API to communicate with mongodb for accessing/storing/retrieving data.
- Open Git Bash inside projectUI and run "npm start". This will start the UI after the webpack is compiled successfully.
- Go to 'http://localhost:4200/ ' on the browser to view the Home Page of "Nu Hideout" Website Application and perform the necessary operations.

#Default Credentials to explore the application (from data\db folder obtained from zip) 
1. Username: kabra.p@gmail.com Password: asdf 2. Username: jonhwick@gmail.com Password: asdf

References:
- https://www.codementor.io/olatundegaruba/nodejs-restful-apis-in-10-minutes-q0sgsfhbd
- https://developers.google.com/places/web-service/search
- https://github.com/googlemaps/google-maps-services-js
- https://googlemaps.github.io/google-maps-services-js/docs/GoogleMapsClient.html
- https://angular.io/guide/router
- http://mongoosejs.com/docs/populate.html
- http://mongoosejs.com/docs/documents.html
- https://coursework.vschool.io/mongoose-crud/
- http://jasonwatmore.com/post/2017/06/25/angular-2-4-alert-toaster-notifications
- https://angular.io/guide/router
- https://github.com/daneden/animate.css
- https://angular.io/guide/http
- https://medium.com/@stefanledin/how-to-solve-the-unknown-modifier-pushall-error-in-mongoose-d631489f85c0
- https://angular.io/guide/reactive-forms
- https://stackoverflow.com/questions/41286853/typewriter-effect-in-angular-2\
- https://www.sparksuite.com/open-source/invoice.html
- https://stackoverflow.com/questions/41379274/print-html-template-in-angular-2-ng-print-in-angular-2

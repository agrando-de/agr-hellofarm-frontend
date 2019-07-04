# hellofarm-frontend

This is a small project for recruitment interview purposes at Agrando. It's created with vue-cli and includes vue-router and vuex.

## Setup & Development

##### Setup
```
npm install
```

##### Compiles and hot-reloads for development
```
npm  run serve
```

##### Compiles and minifies for production
```
npm run build
```

##### Lints and fixes files
```
npm run lint
```

##### Run your unit tests
```
npm run test:unit
```

## Assignment
The overall aim is to create a web-app to keep track of how many animals we have on our farm. This project includes Vuex and Vue Router. You're free to use them as you see fit and also install any further packages. In the end it could look similar to this:
![hello-Farm-Example.png](https://i.ibb.co/H7R88DS/hello-Farm-Example.png).

The following tasks should be completed in order. The aim of this assignment is not to complete as many tasks as possible, but to write sensible code, create a working application and gain a better understanding of what it would be like to work together.

1. **Create a main page with counters for at least 3 species of animals, pigs, cows and sheep.**

 Each counter starts out with 0 and consists of a button to increase the amount, a text showcasing the current amount and a button to decrease the amount. You should not be able to decrease the amount below 0.
 
 
2. **Save the state of your farm manager on firebase.** 

Add a submit button to your page. When the user presses the button the app should send a PUT request with the state of your counters to the endpoint `https://hello-farm-ceb1d.firebaseio.com/farms/<your-farm-name>.json`. You can choose the name of your farm yourself. While the request happens the user should see some kind of indicator that the app is loading.


3. **Load the current state of your farm from the backend.**

Your app should load the current state of your farm before enabling the user to change it. You can load the current state by doing a GET request for `https://hello-farm-ceb1d.firebaseio.com/farms/<your-farm-name>.json`.
 

4. **Create a second page to show the current state of your Farm (no styling necessary).** 

After submitting the state the user should be automatically redirected to this `status` page. The page should have a link back to the page with the counters


**Bonus:**
* Add Animal pictures (provided in the folder `src/assets/images`) to the buttons to make them prettier
* Add sensible tests (Jest testing is already set up)


## Misc
Icons used are from [icons8](https://icons8.com)

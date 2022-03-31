
## CRWN-Clothing-graph-ql
![Crwn-clothing](https://i.imgur.com/2BZ7sKi.png)

[View it Live](https://crown-clthing.herokuapp.com/)

Clothing shop made using React & firebase with Stripe payments implemented. It features Authentication with Google account , Authentication with email & password, Persistant data with local storage, Asynchronous events handling, Paypal payments with Stripe, Performance improvement with lazy loading. This implementation is made using GraphQL for data managment. Also this repository is just the frontend of the whole App. 

**Deployment**: _Heroku_  
**Design**: _Sass & Styled Components_  
**Authentication**: _Firebase auth_  
**Database**: _Firebase Firestore_  
**Backend**: _Firebase & NodeJs_  
**Libraries**:  
- **redux-logger**: console logging redux data flow  
- **redux**: state management  
- **redux-thunk**: handling asynchronous events  
- **redux-saga**: handling asynchronous events keeping actions pure  
- **axios**: implement api requests with ease  
- **reselect**: reusing redux selectors in a performant way  
- **redux-persist**: storing data in local storage  
- **styled-components**: styling components with SCSS
- **react-router-dom**: page navigation
- **react-stripe-checkout**: stripe integration
- **apollo-boost**: graphQL apollo client
- **graphql**: graphQL for data managment

## How to navigate this project  

- the `src` folder is broken down into:
		- `App` - whole app and app container moved to 	  it's own folder
		- `assets` - contains all images used by the app
		- `components` - all reusable components of the web app
		- `firebase` - firebase configuration and utils
		- `graphql` - all graphQL utils and setup
		- `pages` - application pages
		- `redux` - redux reducers, actions, sagas. All data managment logic is replaced with GraphQL in this repository
- The project uses SCSS and styled-components for the overall look of the frontend part of the app. [Example of the cart dropdown component](https://github.com/obleey/crwn-clothing-graph-ql/blob/main/src/components/cart-dropdown/cart-dropdown.styles.scss)
- GraphQL logic is found [here](https://github.com/obleey/crwn-clothing-graph-ql/tree/main/src/graphql)
- All separate pages are found [here](https://github.com/obleey/crwn-clothing-graph-ql/tree/main/src/pages). The app uses React-router-dom for page navigation

## If I had more time I would change this  
- Write all tests using Jest
- Try implementing React-query for data management, upgrade react-router-dom to v6 or maybe replace it with React-location
- use a CSS framework like TailwindCSS or MaterialUI
 
## Available Scripts  
First of all clone or fork this repo and install all the needed dependencies using `npm` or `yarn`

    #1. clone this project
    ~ git clone git@github.com:obleey/crwn-clothing-graph-ql.git

    #2. cd into it
    ~ cd crwn-clothing

    #3. install dependencies
    ~ yarn
    
    #4. run app 
    ~ yarn start

## Authors
[Miha Oblišar - @mihaoblisar](www.linkedin.com/in/miha-obli%C5%A1ar-8b177610a)

## Licence
This project is open-sourced under the [MIT license](https://opensource.org/licenses/MIT).


1. List Products

   1. create product array
   2. add prodcut image
   3. render products
   4. style products

2. Add Routing

   1. npm i react-router-dom
   2. create route for home screen
   3. create router for product screen

3. Create Node.js Server

   1. run npm init in root folder
   2. Update package.json set type : module
   3. Add .js to imports
   4. npm install express
   5. create server.js
   6. add start command as node backend/server.js
   7. require express
   8. create route for / return backend is ready
   9. move products.js from front end to backend
   10. create route for /api/products
   11. rerurns products
   12. run npm start

4. Fetch producs from backend

   1. set proxy in package.json
   2. npm instal axios
   3. use state hook
   4. use effect hook
   5. use reducer hook

5. Manage state by reducer hook

   1. define reducer
   2. update fetch data
   3. get state fro usReducer

6. Create Product and Rating Component

   1. create rating component
   2. create product component
   3. use rating component in product component

7. Create Product Screen

   1. fetch products from the backend
   2. create 3 column for image, info and action

8. Create Loading and Message Component

   1. create loading component
   2. use spinner component
   3. create message component
   4. create util.js to define getError function
      (back 4)

9. Implement Addd To Cart

   1. Create React Context
   2. define reducer
   3. create store provider
   4. implement add to cart button click handler

10. Complete Add To Cart

    1. check exist item in the cart
    2. check count in stock backend

11. Create Cart Screen

    1. create 2 columns
    2. display items list
    3. create action column

12. Complete Cart Screen

    1. click handler for inc/dec item
    2. click handler for remove item
    3. click handler checkout

13. Create Signin Screen

    1. create sign in form
    2. add email and password
    3. add signup button

14. Connect To MongoDB database

    1. create atlas mongodob
    2. install local mongodb database
    3. npm install mongoose
    4. connect to mongodb database

15. Seed Sample Data

    1. create product model
    2. create user model
    3. create send route
    4. use route in server.js
    5. seed sample product

16. Seed sample user

    1. create user model
    2. seed sample users
    3. create user routes
    4. install bycryptjs for encrypting the password

17. Create Signin Backend API

    1. create signin api
    2. npm install jsonwebtoken
    3. define generateToken

18. Create Shipping Screen

    1. create form inputs
    2. handle save shipping address
    3. add checkout wizard bar

19. Create SignUp Screen

    1. create input forms
    2. handle submit
    3. create backend api

20. Implement Select Payment Method Screen

    1. create inputforms
    2. habdle submit

21. Create Place Order Screen

    1. show cart items, payment and address
    2. handle place order action
    3. create order create api

22. Implement Place Order Action

    1. handle place order action
    2. create order create api

23. Create Order Screen

    1. create backend api for order/:id
    2. fetch order api in frontend
    3. show order information in 2 columns

24. Pay Order By PayPal

    1. generate paypal client id
    2. create api to return client id
    3. install react-paypal-js
    4. use PayPalScriptProvider in index.js
    5. usePayPalScriptReducer in OrderScreen
    6. implement loadPayPalScript function
    7. render paypal button
    8. implement onApprove payment function
    9. create pay order api in backend

25. Dispaly Order History

    1. create order screen
    2. create order history api
    3. use api in the frontend

26. Create Profile Screen

    1. get user info from context
    2. show user information
    3. create user update api
    4. update user info

27. Hosting to Heroku

28. Add Sidebar and Search Box

    1. add sidebar
    2. add searchbox

29. Create Search Screen
    1. show filters
    2. create api for search products
    3. display results

# Automate Amazon like E-Commerce Website with Selenium WebDriver

We have created this post as a 'Self Learning Project Assignment' for the automation geeks.

In this project assignment, you will learn to automate different functionalities of an e-commerce website. This assignment is rated as 'Pro' level, which means you should have sound knowledge of all the Selenium concepts. We'll create test plan and then automate an e-commerce website which is quite similar to amazon.com.

## Inspiration

https://www.techlistic.com/p/selenium-assignments.html

## Laboratory

Try automating the above scenarios using Selenium commands, if you face any difficulty please refer the Selenium Tutorial series.

## Web

- https://github.com/jrichardsz/ecommerce-sample

Follow the readme and start it!!

### (+) Automate User Registration process of e-commerce website

Steps to Automate:

1. Open this url http://localhost:4000 .
2. Click on "sign in" link.
3. Click on "No account? Register here" link.
4. Enter your credentials.
5. Click on Register button.
6. Validate if the page show the next message "Great! Now check your email (your email) to complete registration.".

### (-) Verify invalid email address error.

Steps to Automate:

1. Open this url http://localhost:4000 .
2. Click on "sign in" link.
3. Click on "No account? Register here" link.
4. Enter your credentials.
5. Enter a invalid email, for example "user".
6. Validates that the button is disabled.

### (-) Verify that when the account is registered with missing data it does not send to start session

Steps to Automate:

1. Clone this repository https://github.com/sumitkumar1503/ecommerce, and run this ecommerce .
2. Open this url http://localhost:8000 .
3. Click on 'Sign up' link.
4. Enter the user data leaving the address empty.
5. Click in create button.
6. Verify the cursor has passed to 'address' and that the URL has not changed.

### (-) Verify the error messages for entering invalid email

Steps to Automate:

1. Open this url http://automationpractice.com/index.php
2. Click on 'Sign in' link.
3. Enter invalid email address and click 'Create an account' button.
4. Check verify that the error messages for the wrong email are displayed


## Test cases for products
---
### (+) Verify that product can be registered

Steps to Automate:

1. Open this url http://localhost:8000/adminlogin (ecommerce)
2. Enter credentials (user: admin | password: javaisthebest)
3. Go to 'Products'
4. Click button with icon plus (+)
5. Enter product data (name, description, price and image)
6. Click ADD button
7. Verify that the product was added

### (+) Verify product search

Steps to Automate:

1. Open this url http://127.0.0.1:8000/ (ecommerce)
2. Go to search box product
3. Enter the name product search
4. Click button search with magnifying glass icon
5. Verify that the product to search for is in the list of results

### (+) Verify that the product can be modified

Steps to Automate:

1. Open this url http://localhost:8000/adminlogin (ecommerce)
2. Enter credentials (user: admin | password: javaisthebest)
3. Go to 'Products'
4. Select first product and click button update
5. Change name and price product
6. Click update button
7. Verify that the product was added to the table 

### (+) Verify that the product can be removed

Steps to Automate:

1. Open this url http://localhost:8000/adminlogin (ecommerce)
2. Enter credentials (user: admin | password: javaisthebest)
3. Go to 'Products'
4. Select first product and click button delete
5. Verify that the product was removed
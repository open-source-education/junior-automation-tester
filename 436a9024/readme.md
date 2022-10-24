# Automate Amazon like E-Commerce Website with Selenium WebDriver

We have created this post as a 'Self Learning Project Assignment' for the automation geeks.

In this project assignment, you will learn to automate different functionalities of an e-commerce website. This assignment is rated as 'Pro' level, which means you should have sound knowledge of all the Selenium concepts. We'll create test plan and then automate an e-commerce website which is quite similar to amazon.com.

## Inspiration

- https://www.techlistic.com/p/selenium-assignments.html
- https://www.softwaretestinghelp.com/ecommerce-testing/

## Laboratory

Try automating the above scenarios using Selenium commands, if you face any difficulty please refer the Selenium Tutorial series.

## Web

- https://github.com/shopping-apps/ecommerce

Follow the readme and start it!!

### (+)Automate User Registration process of e-commerce website

Steps to Automate:

1. Open this url  http://localhost:4000 .
2. Click on "sign in" link.
3. Click on "No account? Register here" link.
4. Enter your credentials.
5. Click on Register button.
6. Validate if the page show the next message "Great! Now check your email (your email) to complete registration.".

### (-)Verify invalid email address error.

Steps to Automate:

1. Open this url  http://localhost:4000 .
2. Click on "sign in" link.
3. Click on "No account? Register here" link.
4. Enter your credentials.
5. Enter a invalid email, for example "user".
6. Validates that the button is disabled.


### (-)Verify error messages for mandatory fields.

Steps to Automate:

1. Open this url  http://automationpractice.com/index.php
2. Click on sign in link.
3. Enter email address and click Register button.
4. Leave the mandatory fields (marked with *) blank and click Register button.
5. Verify that error has been displayed for the mandatory fields.

### (-)Verify error messages for entering incorrect values in fields.

Steps to Automate:

1. Open this url  http://automationpractice.com/index.php
2. Click on sign in link.
3. Enter email address and click Register button.
4. Enter incorrect values in fields like., enter numbers in first and last name, city field etc., and enter alphabets in Mobile no, Zip postal code etc., and click on 'Register' button.
5. Verify that error messages fpr respective fields are displaying.
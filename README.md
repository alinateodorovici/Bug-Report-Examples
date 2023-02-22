
# Bug-Report-Examples 

**ID** 1

**Status:** Open

**Priority:** P2

**Severity:** S2

**Summary:**
Value inside the username/password field is not deleted when pressing X button.

**Description:**
When user tries to press X button, the text is not erased.

**Assignee:** Developer

**Steps to reproduce:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Write any text in the username/password field
5. Click on X button 

**Expected result:**
Value is erased from the field.

**Actual result:**
 When pressing X button, value is not erased from the field
 
**Test Data:**
user: alina pass: 12345

-------


**ID** 2

**Status:** Open

**Priority:** P3

**Severity:** S3

**Summary:** Incorrect error message is displayed when the username and password are not entered

**Description:**
When the user is trying to login on www.website.com it takes too much time, aproxximattely 1 minute.

**Assignee:** Developer

**Steps to reproduce:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Do not fill any value in user and password fields
5. Click Login button

**Expected result:**
Error message should be displayed: " Epic sadface: Username and password is required"

**Actual result:**
 Error message is displayed, mentioning only username: "Epic sadface: Username is required"
 
**Test Data:**
N/A

--------

**ID** 3

**Status:** Open

**Priority:** P2

**Severity:** S2

**Summary:** There is no maximum character limit for the username and password fields.

**Description:**
User can enter an unlimited number of characters for username and password fields.

**Assignee:** Developer

**Steps to reproduce:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Check how many characters user can fill in username and password fields.

**Expected result:**
A limited number of characters can be entered (according to the specifications).

**Actual result:**
Unlimited number of charachters can be entered in username and password fields.
 
**Test Data:**
N/A

-----------

**ID** 4

**Status:** Open

**Priority:** P2

**Severity:** S2

**Summary:**
Product is not deleted from the cart

**Description:**
When user tries to remove a product from cart, the product is not deleted

**Assignee:** Developer

**Steps to reproduce:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. Click on "Add to cart" button for a product
7. Click on "Remove" button

**Expected result:**
The product is deleted from cart.

**Actual result:**
When clicking on Remove button, the product is not deleted from cart.
 
**Test Data:**
user: problem_user

pass: secret_sauce


-------

**ID** 5

**Status:** Open

**Priority:** P2

**Severity:** S2

**Summary:**
After adding 4 items to cart, user can't add any other items.

**Description:**
User is not able to add more than 4 products in shopping cart.

**Assignee:** Developer

**Steps to reproduce:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. Click on "Add to cart" button for minimum 4 products
7. Try to add another product in cart


**Expected result:**
User is able to add articles in cart

**Actual result:**
After adding 4 items in cart, user is not able to add more products in cart.

**Test Data:**

user: problem_user

pass: secret_sauce

-------

**ID** 6

**Status:** Open

**Priority:** P2

**Severity:** S2

**Summary:**
Product pictures are not relevant.

**Description:**
Instead of a relevant picture of the products, a picture of a dog is displayed.

**Assignee:** Developer

**Steps to reproduce:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. Observe pictures for all products

**Expected result:**
Relevant picture for every product is displayed.

**Actual result:**
A picture with a dog is displayed for all products, instead of relevant pictures with the product.

**Test Data:**

user: problem_user

pass: secret_sauce

-------

**ID** 7

**Status:** Open

**Priority:** P2

**Severity:** S2

**Summary:**
Not all products can be added to the cart.

**Description:**
When trying to click "Add to cart" for some products, nothing happens.

**Assignee:** Developer

**Steps to reproduce:**
1. Login with user
2. Click "Add to cart" button for products: Sauce Labs Bolt T-shirt, Sauce Labs Fleece Jacket, Test.allTheThings() T-Shirt (Red)

**Expected result:**
Products are added to cart.

**Actual result:**
Products are not added to cart

**Test Data:**

user: problem_user

pass: secret_sauce

-------

**ID** 8

**Status:** Open

**Priority:** P1

**Severity:** S1

**Summary:**
User is not able fill in a value in "Last Name" field from checkout page.

**Description:**
When user tries to fill in "Last Name" field in checkout, everything written is displayed in the field above (First Name).

**Assignee:** Developer

**Steps to reproduce:**
1. Login
2. Click "Add to cart" button for a product
3. CLick on cart
4. Click "Checkout"
5. Fill in a value in Name, Last Name and Zip/Postal Code mandatory fields

**Expected result:**
User is able to fill in Name, Last Name, Zip/Postal code mandatory fields.

**Actual result:**
 When trying to fill in a value in "Last Name" field, the actual value is displayed in "First Name" field.
 
**Test Data:**

user: problem_user

pass: secret_sauce

-------

**ID** 9

**Status:** Open

**Priority:** P2

**Severity:** S2

**Summary:**
404 Error is displayed when clicking "About" submenu.

**Description:**
User cannot see related information about the company in the "About" menu section.

**Assignee:** Developer

**Steps to reproduce:**
1. Login
2. Click on side Menu
3. Click "About"

**Expected result:**
User is redirected to company information page.

**Actual result:**
 404 error is thrown.
 
**Test Data:**

user: problem_user

pass: secret_sauce

-------

**ID** 10

**Status:** Open

**Priority:** P3

**Severity:** S3

**Summary:**
"High to low price" sorting option is not working properly.

**Description:**
When user is selecting "Price (high to low)" sorting option, items are not displayed by high to low price.

**Assignee:** Developer

**Steps to reproduce:**
1. Login
2. Click on Price (high to low) sorting option (right corner)

**Expected result:**
Products are displayed by high to low price.

**Actual result:**
 Products are not displayed by high to low price.

**Test Data:**

user: problem_user

pass: secret_sauce

-------


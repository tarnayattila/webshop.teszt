Login / Registration Test Cases
  Feature: User Login

  Test environment: Chrome / Windows / (https://www.saucedemo.com/)
 Test type: Manual testing

 Screenshotok 
  -Test Case 1: Successful login with valid credentials

Precondition:
User is registered in the system.

Test Steps:

Open login page
Enter valid username
Enter valid password
Click on “Login” button

Expected Result:
User is successfully logged in and redirected to the dashboard/home page.

Actual Result:
User is logged in successfully and redirected to the home page.

-Test Case 2: Login with invalid username

Test Steps:

Open login page
Enter invalid username
Enter valid password
Click on “Login” button

Expected Result:
Login fails and system displays an error message (e.g. “Invalid username or password”).

Actual Result:
Login is blocked and error message is displayed.

-Test Case 3: Login with invalid password

Test Steps:

Open login page
Enter valid username
Enter invalid password
Click on “Login” button

Expected Result:
Login fails and error message is shown.

Actual Result:
Login is rejected with proper error message.

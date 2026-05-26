Login / Registration Test Cases
  Feature: User Login

  Test environment: Chrome / Windows / (https://www.saucedemo.com/)
 Test type: Manual testing

    Screenshotok:
<img width="1800" height="1141" alt="Képernyőkép 2026-05-26 092322" src="https://github.com/user-attachments/assets/3236925f-bb0a-4b5a-9aab-5a886d7de10e" />
<img width="1731" height="748" alt="Képernyőkép 2026-05-26 092251" src="https://github.com/user-attachments/assets/527d06ce-e3cd-4efc-bc1f-185525070acc" />
<img width="1789" height="1132" alt="Képernyőkép 2026-05-26 092221" src="https://github.com/user-attachments/assets/4e31c759-315b-4595-ab9d-ab21bfd6b1f9" />
<img width="1783" height="1134" alt="Képernyőkép 2026-05-26 092205" src="https://github.com/user-attachments/assets/89120695-423b-4128-b241-21eeb89b46f0" />
<img width="1205" height="753" alt="Képernyőkép 2026-05-26 092152" src="https://github.com/user-attachments/assets/716d668e-7185-45bd-8929-7bf06e209be1" />

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

# 121 Exam
* PHP Login

---
### Features

##### home.php
Features | Description | Status
--- | --- | ---
1 | No user logged in, display 2 input fields (username and password) | NO
2 | User logged in, display greeting message to user (full name) + email of user | NO
3 | Logout button | NO

##### register.php
Features | Description | Status
--- | --- | ---
1 | No user logged in, display 2 input fields (username and password) | NO
2 | User logged in, display greeting message to user (full name) + email of user | NO
3 | Logout button | NO

##### Fields for registering an account
Features | Field | Requirement | Status
--- | --- | --- | ---
1 | Username | Required + Contain numbers and letters but cannot start with a number + must be unique + Contain 4-10 characters | NO
2 | Password | Required + Contain 5 or more characters | NO
3 | Confirm Password | Must be the same password | NO
4 | Email | Required + Valid email address | NO
5 | First Name | Required + Contain 1 or more character | NO
6 | Middle Initial | Required + Contain 1 letter | NO
7 | Last Name | Required + Contain 1 or more character | NO
* If any of the following requirements are not met, account will not be registered, and appropriate error message/s will be displayed
* Fields will not be deleted if error messages show
* This page cannot be accessed while a user is logged in (user will be redirected to home.php if he tries to access this page)

##### Account Info
* Stored in an XML file called accounts.xml

##### Storing Password
* Use md5() function of PHP to store the password

##### Grading
* Only functionalities of the site will be graded
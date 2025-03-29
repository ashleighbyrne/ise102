ISE102 – Assessment 2 Case Study
You are to develop a banking software application for a major bank in NSW Australia. Your banking
applications will include four major modules which will be addressed in Assessment 2 and 3 respectively.

The modules will include ‘signup, login, deposit and withdraw’.

In Assessment 2, you are to create signup and login modules. The sign-up collects information from the
user while the login cross verifies the input with the registered information. The login will let the verified
user access further banking operation that will be developed in Assessment 3.

Program description: To develop this complete application of login and signup, you will need to develop
appropriate methods for Bank class.



Task 1: Login Module
Create a Bank class with the name (Bank) which can handle login and signup.
For Login:
For task 1, we advise using Username: Joe.Doe and Password: Password123 as testing data for login
attempts. They may be initialized as a verified dummy user in the Bank object.
You need to create a “login” method which takes two arguments – username and password - which will
then be cross verified by the program. If user credentials do not match, it shows an error and requests
the user to re-enter the credentials. If credentials are verified, then the application will take the user to
the main screen (See samples 1 and 2).
You can restrict the password attempts to 3 or leave it infinite. For security reasons, it is often necessary
to limit the password attempts to 3 or less.
In this part of assessments, there is no special requirement for username or password.



Task 2: Signup
This method will ask the user to register him/herself by providing personal information in the form field
or attributes which are Username, Email, Age, Phone, and Password.
1. For this assessment there is no restriction on form fields or attributes.
2. When all given fields provided by the user are entered, you can validate the sign-up by trying to
log in using the same credentials.
3. If any field is empty in the signup process, your software must prompt the user to enter all
details correctly.
4. Once you can sign up and login using your software program, you can provide evidence of code
and all screenshots to demonstrate your work.
5. For advanced students, you can try to use a List to keep more than one user credential (but
there is no extra mark associated with this task).

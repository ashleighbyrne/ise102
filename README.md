ISE102 – Assessment 2 & 3 Case Study

You are to develop a banking software application for a major bank in NSW Australia. Your banking
applications will include four major modules which will be addressed in Assessment 2 and 3 respectively.

The modules will include ‘signup, login, deposit and withdraw’.

In Assessment 2, you are to create signup and login modules. The sign-up collects information from the
user while the login cross verifies the input with the registered information. The login will let the verified
user access further banking operation that will be developed in Assessment 3.


---- Assessment 2 ----

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


---- Assessment 3 ----

Task 1: Deposit Method
Add a ‘deposit’ method to the Bank class.
Your program should prompt the user to enter the amount to deposit to the bank.
Once a valid deposit information is received (e.g., no negative value and non-numerical value),
your program is to add the deposit amount to your total balance.
When user clicks or selects ‘View balance’, they should be able to see the updated balance
amount. Your program needs ‘View balance’ method.
The user can deposit multiple times until select to Quit the program, or you can limit the number
of times a user can deposit in one login session.

Task 2: Withdraw Method
This method will ask the user to enter the amount to withdraw. If the withdrawal input amount is
valid (e.g., non-negative and only numerical value), the withdrawal amount should be deducted
from the total balance. If the total balance becomes negative, the withdraw request should not
be processed. The program should display ‘not sufficient fund available’ message.
Provided the total balance is still positive or zero, the ‘View balance’ option should provide the
updated total balance. You may want to limit the number of withdrawals in your program to
safeguard the software program.
For the security purpose, if non-numerical data is entered to the withdrawal field, the program
should warn the user ‘Only numerical data to be entered for withdrawal’.

Task 3: Unified Modeling Language (UML)
Use a user-case diagram and activity diagram to describe all banking operations and their
interactions with the user. Explain how UML diagrams can be used in program specification
design and program verification and validation. What other UML diagrams can be used in a
similar s/w programming project.

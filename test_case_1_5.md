# MrBuggy3 zadanie #1, #3 
****
### Created by:

***Przemysław Baszyński***
*przemo_@_baszynscy.pl*

### Title / no
***MrBuggy 3, zadanie #1, #3 TC_5***

### Description

Checking if it is possible to create an account with existing user name.

### Precondition

New user account creation form

### User / Roles

New user

### Test Data

User name: *zbyszek*\
Password: *Zbyszek1*\
First name: " "
Last name: " "

### Steps / Action / Expected Result

1. Fill out the form with test data.
2. Send the form by clicking "Zarejestruj użytkownika".
3. After creating a new account tap on link "Zarejestruj kolejnego użytkownika".
4. Fill out the form with the same test data.
5. Expected result: account creation is not possible, the application displays a message - "User name exist in data base".

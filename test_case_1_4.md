# MrBuggy3 zadanie #1, #3 
****
### Created by:

***Przemysław Baszyński***
*przemo_@_baszynscy.pl*

### Title / no
***MrBuggy 3, zadanie #1, #3 TC_4***

### Description

Checking if it is possible to create an account with incorrectly completed fields "First name" and "Last name".

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
3. Expected result: account creation is not possible, the application displays a message about incorrectly completed fields.

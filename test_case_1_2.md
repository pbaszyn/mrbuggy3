# MrBuggy3 zadanie #1
****
### Created by:

***Przemysław Baszyński***
*przemo_@_baszynscy.pl*

### Title / no
***MrBuggy 3, zadanie #1, TC_2***

### Description

Check if it is possible to set up an account without entering the required fields, marked with an asterisk

### Precondition

New user account creation form

### User / Roles

New user

### Test Data

User name: *zbyszek*\
Password: *Zbyszek1*\
First name: *Zbyszek*\
Last name: *Kowalski*

### Steps / Action / Expected Result

1. Fill out the form leaving one of the fields blank.
2. Send the form by clicking "Zarejestruj użytkownika".
3. Repeat steps 1 and 2 leaving the next boxes empty.
4. Expected result: the user cannot be registered without entering one of the required fields.

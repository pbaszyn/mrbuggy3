# MrBuggy3 zadanie #4, #6, #19, #24
****
### Created by:

***Przemysław Baszyński***
*przemo_@_baszynscy.pl*

### Title / no
***MrBuggy 3, zadanie #4, #6, #19, #24 TC_1***

### Description

Bank account number field - validation test

### Precondition

Bank account with some money.
Bank account money transfer form.

### User / Roles

Bank account user.

### Test Data

"Nr rachunku odbiorcy": *89105024841488137640364928*; *8910502484148813764036492*; *abc*; " "\
"Nazwa odbiorcy": *"Jan kowalski"*\
"Adres odbiorcy": *"Poznań, ul. Solna 1"*\
"Tytuł przelewu": *"Test"*\
"Kwota": *"100 PLN"*

### Steps / Action / Expected Result

1. Set up input fields with test data, try different values in "Nr rachunku odbiorcy" field.
2. Tap on "OK" button.

Expected result - the form does not allow to use keys other than numbers, shows error if account number has incorrect format.

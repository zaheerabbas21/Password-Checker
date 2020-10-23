# Password-Checker
Check your password securely without transmitting your password through internet. 
You would need the internet to connect to API and obtain the response.


This project makes you to securely check if your password has been pwned or hacked.
It uses Troy Hunt's **Have I Been Pwned** API to get the passwords that have been leaked in the past using only the first five characters of the SHA1 generated password.

# How is it secure
Well the Troy Hunt's website uses the same technique as this project does i.e, Hash K-anonimity. Although if you are using the website to check Your password. I find it still not 
secure because your password is still transmitting through the Internet.

# How does this project help in this issue
This project is just a single python file that helps us run locally. It uses the API of **Have I Been Pwned** website. Your computer needs to be connected to the Internet.
But your password will not be transmitted through the Internet

# How to use and run this file on your local computer
**Pre-requisites**:
-You should know how to use Power Shell(Windows) or Terminal(Mac). I assume if you are using linux then you know how to use a terminal 😊.

You should copy the **Password Checker.py** file into your local computer. This file contains three main functions. 
1. main_file(filename)
-> Run this function if you have a lot of passwords stored in a file. You should give the filename as command line argument and also the file must be present in the same directory as you are currently running this python script on.
2. main_user_input()
-> Run this function if you want to manually provide the input. Note that this function has an infinite loop. To break out of this you must enter "-1"(without quotes).
3. main_command_line(args)
-> Run this function if you have a small number of passwords. You should give all the passwords that you want to check as command line arguments .

**Uncomment any one of the function call(you can find those below at the bottom of the file) that you want to run and check if your password has been pwned or not securely**

# Testing
**I have tested this file on windows machine. If you are using a different OS and not getting the intended result please revert back it to me so that I can modify this code. Or you are welcome
to fork this repo and do the modification yourself.** You might face this problem if you are using main_file(filename) function because I did not write it using Pathlib module.
So if any problem arises please feel free to revert back to me. My email address is visible on my github account.

**Thank you for visiting this project**

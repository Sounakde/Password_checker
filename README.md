# Password Checker
## Project Description
The Password checker project checks if the password that is given as input has ever been leaked or not in the past. Based on output, the program will confirm if the password can be used for login or not. The project accesses a real time database using 'Have I been pwned' website's api for information and checking of passwords. Modifications can be done to improve the project and if you are not able to, then you can comment with the suggestion.
## Technologies Used
* Python
## Setting Up
### Interpreter
The python interpreter is required to run this program and the link to download the official python is given below
* [Python](https://www.python.org/)

Choose the one you want to download based on your OS and version (32-bit/64-bit for windows only) by clicking on the appropriate link. (To get the 64-bit version for windows click on the windows button and DO NOT hover above it and go to the side under Downloads tab)
### Dependencies
The required dependencies to run the program is given below
* Requests
* Hashlib
* sys

Only the requests library has to be installed using *pip* command. The other two are bult-in libraries.
### Installation
Install the requests library like this

    pip install requests

### Running the program
To run the the program simply type the following command and it will show how many times the password may have been used before
    
    python password_checker.py
### Repl.it URL 
* [![Run on Repl.it](https://repl.it/badge/github/Sounakde/Password_checker)](https://repl.it/github/Sounakde/Password_checker)
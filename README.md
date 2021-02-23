# login-register-system-in-c-
This project is built in C++ programming language, it uses file handling and lets the users login and register into the system, each user has their unique username.
The system is built by using fstream header file and ifstream and ofstream classes,

ifstream filei; //It reads the files through the object 'filei'.
ofstream fileo; //It opens the files through object 'fileo'.

and using methods like open(), fail().

There are two choices to log in or to register if the new user uses the system, it works in a loop until the user decides to leave
the system by pressing any key and pressing enter.
If the user enters the wrong password, then an alert message shows up.

If the user is already registered into the system or the username entered by them is already in use then a message is displayed like in the image below,
the user can't register with the existing username or they can try logging in rather than registering.
If the unregistered user tries to login then the system shows a message instantly.
Note: If you register as a new user then you have to run the code again and log in, then you can view your file.
To exit the application press any key and press enter.
Thank You:), Hope you find it useful and informative.

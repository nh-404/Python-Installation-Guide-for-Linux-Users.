# PythonSetup_Linux

- Python installation guide for linux user. This document describes how to install Pyrhon3 on Ubuntu or debain Linux machines.

# Installation Process

- First of all you should confrom about python3 installation. Is still python3 installed on your machine...?

# Installation check

- open your linux terminal or press and hold (Alt + Ctrl + T). then run follwing this command 

 ```
 $ python3.10 --version
 
  ```
  
  - Conditions :  01
  - if python3 is installed, Then showing this result

 ```
Python 3.10.5 (main, Jun 26 2022, 13:09:33) [GCC 9.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 

 ```
 - Conditions : 02 
 - And python3 is not installed sucecssfully, Then showing this result
 
  ```
python3.10: command not found
  ```
  
  - If conditions : 01 is Okay then you should not install python3.
  -  If conditions : 02 is not Okay. then you should install python3 and then follow this steps.
  
# Step 1: Update and Refresh Repository Lists

- open your linux terminal or press and hold (Alt + Ctrl + T). then run follwing this command 

  ```
  $ sudo apt update
  ```
 # Step 2: Download python3 source file
 
 - Now. one by one copy & paste following commands
 
 - command: 01
 ```
 $cd Downloads/
  ```
  - command: 02
  ```
 $wget https://www.python.org/ftp/python/3.10.5/Python-3.10.5.tgz
 ```
 
 # Step 3: Unzip source file & installation
 
 - Now one by one copy & paste following commands
 
 - command: 01
 ```
  $ tar xvf Python-3.10.5.tgz
  ```
  - command: 02
  ```
  $ cd Python-3.10.5/
  ```
  - command: 03
  ```
  $ ./configure
  ```
  - command:04
  ```
  $ make
  ```
  - command: 05
  ```
  $ sudo make install

 ```
- Allow the process to complete and verify the Python version was installed sucessfully:

# Final Step: sucecssfully python3 installation check

- After done installation now check, is sucecssfully python3 installed or not

 ```
 $ python3 --version
 
  ```

- if python3 is installed sucecssfully, Then showing this result

 ```
Python 3.10.5 (main, Jun 26 2022, 13:09:33) [GCC 9.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 

 ```

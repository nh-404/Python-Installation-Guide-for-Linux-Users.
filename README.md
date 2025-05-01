
<div align = "center">

<img src = "https://github.com/nh-404/Python-Installation-Guide-for-Linux-Users./blob/main/python-logo.png">

</div>

# Python Installation Guide for Linux Users

- This document explains how to install Python 3 on Ubuntu or other Debian-based Linux systems.
 
## Installation Process

- First, confirm whether Python 3 is installed on your system..

## Installation check

- Open your Linux terminal by pressing (Ctrl + Alt + T), then run the following command:
 
 ```
 python3 --version
 
  ```
  
  ### Conditions :  01
  - Check if Python 3 is already installed: No further action is needed install Python3.

 ```
Python 3.10.5 (main, Jun 26 2022, 13:09:33) [GCC 9.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 

 ```
 ### Conditions : 02 
 - If Python 3 isn’t installed, the terminal may display something like this:
 
  ```
python3.10: command not found
  ```
    
  
## Step 1: Download the Python 3 source file from the official Python website.
 
 ```
 https://www.python.org/downloads/source/
  ```

 ## Step 2: Update and Refresh Repository Lists

- open your linux terminal or press and hold  (Alt + Ctrl + T). then run follwing this command.

  ```
  sudo apt update
  ```
  
 ## Step 3: Unzip source file & installation
 
 - Now copy & paste following commands
 
 - Command: 01
 ```
  tar xvf [Downloaded package name. example: Python-3.x.x.tgz]
  ```
  - Command: 02
  ```
  cd [Downloaded package name. example: Python-3.x.x.tgz]
  ```
  - Command: 03
    
  ### To perform a fresh installation of Python:
    
  ```
  ./configure
  ```

  ### To upgrade an existing installation of Python:

   ```
  ./configure --enable-optimizations
  
  ```
 
  - Command:04

  ```
  make
  
  ```

  - Command: 05
    

  ### To perform a fresh installation of Python:
 
  ```
  sudo make install

  ```

   ### To upgrade an existing installation of Python:

  ```
   sudo make altinstall
 
  ```
     

# Final Step: sucecssfully, python3 installation check

- Once the installation is complete, verify that Python 3 was installed successfully.

 ```
 python3 --version
 
  ```

- If Python 3 has been installed successfully, you’ll see the following output:

 ```
Python 3.10.5 (main, Jun 26 2022, 13:09:33) [GCC 9.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 

 ```

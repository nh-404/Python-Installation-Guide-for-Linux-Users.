
# -Python Installation Guide for Linux Users

- This document describes how to install Python3 on Ubuntu or Debian-based Linux systems.
 
# Installation Process

- First of all, you should confirm whether Python3 is installed on your system.

# Installation check

- Open your Linux terminal by pressing and holding (Alt + Ctrl + T), then run the following command:
 
 ```
 python3 --version
 
  ```
  
  - Conditions :  01
  - if python3 is installed, Then showing this result

 ```
Python 3.10.5 (main, Jun 26 2022, 13:09:33) [GCC 9.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 

 ```
 - Conditions : 02 
 - And if Python 3 is not installed successfully, it will display the following result (EXAMPLE):
 
  ```
python3.10: command not found
  ```
  
  - Condition 01: If it is okay, you do not need to install Python3.
  - Condition 02: If it is not okay, you should install Python3 and then follow these steps.
    
  
# Step 1: Download the Python 3 source file from the official Python website.
 
 ```
 https://www.python.org/downloads/source/
  ```

 # Step 2: Update and Refresh Repository Lists

- open your linux terminal or press and hold (Alt + Ctrl + T). then run follwing this command.

  ```
  sudo apt update
  ```
  
 # Step 3: Unzip source file & installation
 
 - Now one by one copy & paste following commands
 
 - Command: 01
 ```
  tar xvf [Downloaded package name. example: Python-3.x.x.tgz]
  ```
  - Command: 02
  ```
  cd [Downloaded package name. example: Python-3.x.x.tgz]
  ```
  - Command: 03
    
  - For a NEW install
    
  ```
  ./configure
  ```

  - To UPGRADE an already installed version

   ```
  ./configure --enable-optimizations
  
  ```
 
  - Command:04

  ```
  make
  
  ```

  - Command: 05
    

  - For a NEW install
 
  ```
  sudo make install

  ```

  - To UPGRADE an already installed version

  ```
   sudo make altinstall
 
  ```
     

# Final Step: sucecssfully, python3 installation check

- After completing the installation, check if Python3 was installed successfully.

 ```
 python3 --version
 
  ```

- If Python3 is installed successfully, it will display the following result:

 ```
Python 3.10.5 (main, Jun 26 2022, 13:09:33) [GCC 9.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 

 ```

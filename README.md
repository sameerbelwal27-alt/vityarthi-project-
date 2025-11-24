# vityarthi-project-
vityarthi  project repository 
# Password Strength Checker
A simple Python project that checks the strength of a user's password based on several security conditions.  
This tool is useful for understanding password security requirements and implementing basic validation in Python applications.

##  Features
- Checks if password length is at least 8 characters  
- Ensures presence of:
  - At least one digit  
  - At least one uppercase letter  
  - At least one lowercase letter  
  - At least one special character  
- Provides meaningful feedback:
  - Weak
  - Medium
  - Strong

##  How It Works
The program evaluates the password through a series of conditions using:
- Python string methods
- Regular expressions (re module)

Based on the conditions met, it returns:
- *Weak* → when major conditions are missing  
- *Medium* → when only special characters are missing  
- *Strong* → when all conditions are satisfied  



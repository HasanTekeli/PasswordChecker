# PasswordChecker
Check if your passwords have been pwned!

This code uses https://haveibeenpwned.com/ to check if your password safe or not.

Your password may be vulnerable to attacks if you check your password on websites, so this script:
  - hashes your password
  - gets the first 5 character of the hash
  - gets the list of hashes that matches the first 5 characters of your hash
  - gets counts of how many times these hashes have been compromised
  - combine the other characters of the hash with the first five characters 
  - and compare it against the downloaded hashes.
  
## To run the script:
  - Open Terminal/Command Prompt on the directory where you saved this script.
  - Run 'passcheck.py yourpassword' without quotations. 

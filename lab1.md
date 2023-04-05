Lab Report 1
============
**Tutorial on logging into a course-specific account on ieng6!**
*Unfortunately I did not go through the trouble of installing VSCode or Git;
however I have included links to their installations!*
[Link] ( https://code.visualstudio.com/)
[Link] (https://gitforwindows.org/)
[Link] (https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994)
**Step 1: Opening Visual Studio Code and Finish Installation**
- The installation steps are explained by the VS installation software
- Once Visual Studio Code is open, it should look something like this:
![Image] (VisualStudio screenshot.png)
*Note: different themes/appearance settings may look different*

**Step 2: Opening up the Terminal in VSCode**
- Open the terminal in VScode by the using the Command "CTRL" or "Command" + ` or use the Terminal -> New Terminal option
- Enter the command "ssh cs15lsp23__@ieng6.ucsd.edu" where the underscores are to be replaced with the letters in your course specific account!
*Note: (That’s one, five, l (lowercase letter L, not one);*
 - Upon entering, you may receive a message that the authenticity of host... you may enter 'yes' to enter
 *Note: This message should only appear upon the first sign on, if it gets repeated, someone may be trying to control the connection!*
  - After entering 'yes' enter your password (Make sure you use the correct password or you will get an error message like this:
  ![Image] (Logging in VS.png)
  *Note: it may not look like you're typing a password, but you are typing a password even if the cursor isn't moving!*
  
  **Step 3: Running Some Commands!**
  - you can try commands such as 'cd' 'ls' 'pwd' 'mkdir' 'cp'
  - a few specific commands you can try are 'cd ~' 'ls -lat' 'ls -a'
  - Commands running may look something like this:
  ![Image] (VSTerminal_Screenshot.png)
  
  **Step 4: Logging off**
  Logging out of the remote server is quite simple using either of the two options:
  - Using the command 'Ctrl-D'
  - Run the command 'exit'
  *Note: you can run multiple terminals in VSCode using the smalle '+' button at the top of the terminal window!*
  
  


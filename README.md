# autoupd
Simple bash script to update and upgrade ubuntu in bash.

To make this executable from anywhere by simply typing 'autoupd', follow these steps:
<br>

Step 1
<br>
Download the file and place it in a folder that it will live permanently, eg `~/scripts`
<br>

Step 2
<br>
Add the filepath to `.bashrc`
<br>

`$ nano .bashrc`

Scroll to the end and add 
<br>
`export PATH=$PATH:~/scripts/`
<br>

Apply the changes
<br>
`source ~/.bashrc`
<br>

Step 3
<br>
Give the script executable rights.
<br>
`chmod u+x ~/scripts/autoupd`

Check the new permissions.
<br>
`$ ls -l ~/scripts/autoupd`
<br>
Output should look like:
<br>
`-rwxrw-r-- 1 user user 697 Oct  8 16:48 autoupd ` note the x for executable
<br>

Success! You should now be able to execute the command autoupd from anywhere

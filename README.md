# set-timezone
Script to change timezone on multiple firewalls

The purpose of this simple script is change de timezone on multiple Check Point (Gaia) firewalls.
It will connect to each appliance through ssh using plink, you can use putty if you don't want to generate a log file with the output of the commands.
You can modify the script to execute any kind of configuration on any appliance that accept SSH connection, just modify the commands on the script.

You will need to have plink.exe, that you can download on Putty website.
https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html

You will also need to create a file called firewalls.txt, where you type all the firewalls IP addresses, one in each line.

Edit the script and replace the word "usuario" by your username and replace "123456" by your password to login to the firewalls.

Finally, To execute the script, change the extension from txt to bat.

The script you generate a file with the output of the commands and the hostname of each firewall. The path is c:\timezone_output.txt.


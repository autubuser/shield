# Tutorial of designated website for PC shielding
#
>  * [Chinese | 简体中文](https://github.com/autubuser/shield/blob/main/README.cn.md)
#

## `Why block malicious websites?`
>  * Nowadays, computers are very popular in homes and offices. You can browse all kinds of websites on the Internet, including many excellent websites, but there are not many websites that are safe for computers or affect physical and mental health. Therefore, we need to block some malicious advertising websites or parents need to block some bad information websites or game websites for the healthy growth of children

#
## `How do we block malicious websites?`
#
>  ###  `Windows Shielding mode`
> 1. Keyboard Shortcuts <kbd>win</kbd> + <kbd>R</kbd> Outgoing operation/terminal
> 
> 2. Then type "hosts" File Path "hosts" File directory
```javascript
C:\WINDOWS\system32\drivers\etc
```
> 3. Open "etc" After folder，stay "hosts" Right click on the file name，Then click "Open Method", and then select "Notepad" to open
> 
> 4. Add a line at the bottom of the file 127.0.0.1 + URL to be blocked，or 0.0.0.0 + The URL to be blocked is OK (the IP address in front and the URL on the right are separated by a space)

#
>  ###  `Macos Shielding mode`
> 1. Open  "application program"，then "Utilities"，Last Open "terminal"
> 
> 2. Open "hosts" file，Enter the following command，Then press <kbd>Enter</kbd> ：In the Lord "terminal" Edit in window "hosts" file
```javascript
sudo nano -e /etc/hosts
```
> 3. Add a line at the bottom of the file 127.0.0.1 + URL to be blocked，or 0.0.0.0 + The URL to be blocked is OK (the IP address in front and the URL on the right are separated by a space)
> 
> 4. Press <kbd>ctrl</kbd> + <kbd>O</kbd> preservation，Then press <kbd>ctrl</kbd> + <kbd>X</kbd> Close File
#
> ## `matters needing attention`
> * Don't take it "http://", For example, if you want to block "google" , this line should be
```javascript
127.0.0.1 www.google.com
```
> * "Hosts" The file only checks the absolute value of your input ULR，for example: "google.com" Do not copy and paste other documents, which may introduce invisible characters, thus affecting the function of the text
> 
> * Open again "hosts" file，Delete the URL entry you want to unmask, save and exit to restore access
#
> ## `Feedback on problems`
> If you have any problems in use, please give me feedback. You can leave a message in the warehouse to communicate with me
#
> ## `Star`
> If you like my work, I hope you can support "Star"
> 
> If you find a new malicious website that needs to be blocked, you are also welcome to 'submit a code' or 'leave a message' and add it to our blocked information sharing directory, so as to contribute to optimizing and creating a green network environment!

#
> ## ```List of "malicious" URLs```
> You can directly copy the data in the "hosts" file and add it to the end of your local "hosts" file, or directly download the "hosts" file to replace it. If you encounter problems, you can search "Google" or "Baidu" to solve them
>
> ### `Explain:`
> * The 'website' information we listed does not mean that all of it is malicious. Some of it is just that we think it may not be suitable for children to contact. If it is offensive or you feel wrongly judged, please contact me and I will delete it!
>
> ### `Warm reminder [disclaimer]:`
> * Any system operation has certain risks. If you are not familiar with the system or are not prepared for it, it is recommended that you do not make any modifications to prevent the system from being damaged so that the function cannot be used normally. Here is only a method to solve the problem of blocking bad information websites. Your attempt to modify the operation shows that you agree with and understand all the risks and consequences that these operations may bring. The author is not responsible for any consequences!
#
> ## `Write at the end:`
> * We can't list all the bad websites and add them to the ban list, but if we can ban one, the possibility of minors or other people facing these "bad information" pollution will be reduced by one! Create a green online environment, green and healthy life, take more children to play sports, participate in various activities, transmit more positive attitude towards life, and guide positively!
#
> ### `If you have a better way to block this information, you are also welcome to share your contribution. Thank you!`
#

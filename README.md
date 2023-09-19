# DVWA

![image](https://github.com/samerkhateeb/DVWA/assets/55295850/5b39b541-4848-4187-ac4f-caaac8525cd3)

Damn Vulnerable Web App (DVWA) is a PHP/MySQL web application that is damn vulnerable. Its main goals are to be an aid for security professionals to test their skills and tools in a legal environment, help web developers better understand the processes of securing web applications, and aid teachers/students in teaching/learning web application security in a classroom environment.

#How To Setup!

Download the DVWA ISO image from the following link:
https://www.vulnhub.com/entry/damn-vulnerable-web-application-dvwa-107,43/

It will download with size (503 MB):

![image](https://github.com/samerkhateeb/DVWA/assets/55295850/ec74fb18-1f4a-46cc-990c-9c7b37b61d6f)

open VBOX, and click on New:

![image](https://github.com/samerkhateeb/DVWA/assets/55295850/08f752ce-921f-45c7-93d0-5acb90ca50e5)

Then add the following:
1. Fill in the Name, and choose something unique to be saved in your environment.
2. in the ISO Image, please select the ISO image you've downloaded from the previous link:
![image](https://github.com/samerkhateeb/DVWA/assets/55295850/86874818-4538-4d92-b3e2-23bdb82b6811)


Note: in the "Folder" this will be automatically selected based on your environment, keep it as is.

Click Next !

Now you will see the screen Setup the Hardware:
![image](https://github.com/samerkhateeb/DVWA/assets/55295850/5a6aff77-f45d-423c-b0b3-c222a567c39a)

Put 512MB for Base Memory, and Processer 1 CPU.
Click Next

Virtual Hard Setup,
- Create a Virtual Hard Disk Now
- Put the size  25GB, this is just a virtual drive,
![image](https://github.com/samerkhateeb/DVWA/assets/55295850/744e21cb-bac5-41f7-adb9-baceb787fe58)

Note: Don't check Pre-allocate Full Size if you do not have space in your computer, it will allocate an unnecessary 25GB from your hard disk.

Summary:
![image](https://github.com/samerkhateeb/DVWA/assets/55295850/cd1301c7-6c1c-499e-97db-86a469b67187)

Now, we need to start and set the machine:
![image](https://github.com/samerkhateeb/DVWA/assets/55295850/286f6333-a10e-4fa7-a327-22b80ea72c0c)

Next, wait 15 seconds until this load finishes.

![image](https://github.com/samerkhateeb/DVWA/assets/55295850/b84a39ba-dff0-493b-b5bf-7b0f5da1c75a)


Now, click on the second option "Install Start the installer directory":

![image](https://github.com/samerkhateeb/DVWA/assets/55295850/566fb05a-6611-492f-aefd-fb34d958d253)

now, the virtual machine will be the following:

![image](https://github.com/samerkhateeb/DVWA/assets/55295850/68d806d1-7ced-4c0c-aed2-da44b4a4583e)

Type "do-release-upgrade"
Type the password: password

Wait until the setup is completed


![image](https://github.com/samerkhateeb/DVWA/assets/55295850/20ae1db1-d4d3-4b46-bc45-2ca38a7af71b)


After it's finished, go to Network and change the option to "Bridge Adapter":

![image](https://github.com/samerkhateeb/DVWA/assets/55295850/a349d6ba-b219-4f11-b5a3-350118935c43)


Restart the machine:
![image](https://github.com/samerkhateeb/DVWA/assets/55295850/3f5a7aa3-1bf8-4af0-af79-98e681262b90)


Select the first option this  time:
![image](https://github.com/samerkhateeb/DVWA/assets/55295850/b3580a53-da27-494f-84c2-37b953a44480)

whent the page opened, type ifconfig

![image](https://github.com/samerkhateeb/DVWA/assets/55295850/8c5b6fb1-4d38-49dd-b695-57bfb8e819ab)


then you should find your IP address, type the url:

![image](https://github.com/samerkhateeb/DVWA/assets/55295850/ab46109e-d3cf-44c0-b962-ddaaad2cd629)


then it will open the login page,
use the following credentials:
username: admin
password: password

BOOM !!!!

![image](https://github.com/samerkhateeb/DVWA/assets/55295850/de5c42d7-50e3-4254-8678-a7b80bef6077)






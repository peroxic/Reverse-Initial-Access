# Reverse-Initial-Access [R.I.A]
![image](https://github.com/user-attachments/assets/4311bcd1-4933-4d32-b447-c7b9ca7b7d1c)

# Use Cases
Say youre on a red-teaming operation, you need initial access to a system but the system is using a common anti-virus or EDR solution, this repo is designed to help you get around those protections to gain intial access to those systems leveraging built in utiities like cmd.exe and powershell.exe.
Keep in mind 99% of these scripts are meant to be used on Windows machines, as it is the most common used ating system. Some might work on windows 10 but not windows 11, if it doesnt work on win10 but win11 or the other way around, please modify the scripts to make them work on the target OS, make a pull request and I will make sure to look at it and accept it.

# Necessary information
These scripts and the code are meant to be used on Windows based machines like Windows 10 and 11.
This repo is specifically meant only for intial access, nothing in this repo will have built in persistence or anything like that, just initial access to establish other thingsl ike persistence.
You will need the raw shellcode for this to work, preferably msfvenom meterpreter shellcode, cobalt strike shellcode will work too or even binary converted to shellcode.

# How to use
self explanatory, if you dont know how to use this repo properly, then you are in the wrong place.

# Compatible Software
Currently unknown but i would say the follow are all compatible:
* Cobalt Stike
* Havoc C2
* Brute Ratel C4
* Nighthawk C2
* Sliver C2
* Covenant C2
pretty much any post exploitation framework that generates a .bin shellcode file. 

* Listeners
I recommend using netcat or a python server, but using an RDP with the necessary open ports and using the RDP Public IP works jut aswell.


* Disclosure
I am in no way shape or form responsible for anyone who uses anything inside of my profile or this repo, this repo and my profile is meant to help red and blue teamers and educate people on this type of attack(s) and how people can leverage things on your system to attack you and others. I do not promote or am okay with any user(s) using this repo or any other repo I post or create for illegal purposes or in any non-ethical way.

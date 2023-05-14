# System Hacking
## System Hacking
- is defined as the compromise between computer systems and software to access the target computer and steal or misuse their sensitive information.
- The malware and the attacker identify and exploit the vulnerability of the computer system to gain unauthorized access.
- Here the malicious hacker exploits the weaknesses in a computer system or network to gain unauthorized access to its data or take illegal advantage.
## Linux System Hacking
- As we all know, Linux is an Operating System (OS) assembled user the model of open-source software development and distribution and is based on Unix OS created by Linus Torvalds.
- Now to hack a Linux-based computer system and get access to a password protected Linux system, we have to know Linux's basic file structure.
- As we know, Linux is considered to be the most secure OS to be hacked or cracked, but in the world of Hacking, nothing is 100% secured.
- Hackers usually use the following techniques to hack the linux system.
  - Hack Linux using the SHADOW file.
  - Another technique commonly used by hackers is to bypass the user password option in Linux.(Privilege Escalation)
  - In another technique, the hacker detects the bug on Linux distribution and tries to take advantage of it.
## Windows Hacking
- The user password of Windows OS, which appears after the Windows starts logging in, lets users protect the computer from getting unauthorized access.
- Choosing a strong password of more than eight digits is an excellent practice.
- Henceforth you can protect your files and folders from the hands of malicious users.
- There are several tricks and techniques to crack a windows password. But, from the hacker's point of view, if you can use social engineer your victim and find a Windows computer open, you can easily modify the existing password and give a new password that will be unaware of the victim or the owner of the computer.
- Also There is a simple method to bypass windows login
## Reverse Shells
- As we saw shells are The only way to interact with the kernel.
- A reverse shell, also known as a remote shell or “connect-back shell,” takes advantage of the target system's vulnerabilities to initiate a shell session and then access the victim's computer.
- Reverse shells allow attackers to open ports to the target machines, forcing communication and enabling a complete takeover of the target machine.
- Therefore it is a severe security threat.
- This method is also commonly used in penetration tests.
## Netcat
- Netcat is a Command-line Interface (CLI) Based tool that is use to
read/write data over TCP/UDP.
● It is a Back-End tool which can smoothly be cross utilized by other
programs
● It is a tool That helps to create Reverse shells or Bind shells
● It is built in on kali and parrot but for windows you have to download it.
Web servers
● On the hardware side, a web server is a computer that stores web server
software and a website's component files (for example, HTML
documents, images, CSS stylesheets, and JavaScript files).
● A web server connects to the Internet and supports physical data
interchange with other devices connected to the web.
● It is A computer software and hardware that uses HTTP and HTTPS to
provide a website.
● There are a lot of softwares that can be installed on the server to work like
webserver
A. Apache server
● This Server software will help to provide Web contents.
● On linux it comes Built in
● But on windows you can install it with softwares called Xampp and
wampp and will give you localhost web contents
● To Start this server software
Web Server - apache
● By going to out IP on any browser we can get a
websites.
● The default path of apache2 is /var/www/html
● So on any webserver the websites are running on
This path.
● The website you see on the right side is the default
web for apache2 the file for this is the “index.html”
from the /var/www/html file
B. Python Server
● We can you python to start web servers
● To start the service
● The python will help you to host website from any path on your computer with any
port you need.
○ Example: on the above command i started the web server in ~/rex folder with port 9090
○ So to access the website i need to type the port with the ip
■ 192.168.1.7:9090 => will be the site for this
CVE
● CVE stands for Common Vulnerabilities and Exposures.
● CVE is a glossary that classifies vulnerabilities.
● The glossary analyzes vulnerabilities and then uses the Common Vulnerability
Scoring System (CVSS) to evaluate the threat level of a vulnerability.
● The CVE glossary is a project dedicated to tracking and cataloging vulnerabilities in consumer software
and hardware.
● It is maintained by the MITRE Corporation with funding from the US Division of Homeland Security.
● Vulnerabilities are collected and cataloged using the Security Content Automation Protocol (SCAP).
● SCAP evaluates vulnerability information and assigns each vulnerability a unique identifier.
Metasploit
● The Metasploit framework is a very powerful tool which can be used by cybercriminals
as well as ethical hackers to probe systematic vulnerabilities on networks and servers.
● Because it’s an open-source framework, it can be easily customized and used with most
operating systems.
● It is written with ruby.
● It have a lot of exploits for different kind of vulnerabilities and CVE’s
● It Provides you
○ Exploits,
○ Payloads: a program that helps to run after exploiting/getting reverse-shells
○ Auxiliarys: Programs That will help to scan further on the system.
○ Encoders,
○ Listners,
○ Post-exploitation codes: Used to run after we Exploit / privilege Escalation
Start.
● ON kali/parrot it is already installed,
● To start it just type, “msfconsole”
● We can search any exploit for a system.
○ Example: for apache
○ “search apache”
● Metasploit is a very old tool and even the encoders are
very old.
● This means almost every users tried them and exploited
for some time but now a days all the antivirus and
Microsoft defender will stop them and detect them.
● But it is Still handly tool for other exploitation and
Scanning, you will see it in the future use.
● If you want to test these encoders on your system(may be
if it is vulnerable for some of them.)
● Just add -e and the encoder name from the list and create
the payload.(msfvenom)
Payload on WAN.
● As you saw we were trying the payloads on LAN network. Does it run on
WAN?
● TO do this we will need a thing called port forwarding.
● Port forwarding inherently gives people outside of your network more access to
your computer. Giving access or accessing unsafe ports can be risky, as threat actors
and other people with malicious intents can then easily get full control of your device
Ngrok
● Ngrok is one of the portforwarding tools.
○ You can host websites with it
○ You can listen to tcp connections
● To setup:
○ GOTO their website & create account
■ https://ngrok.com/
○ Verify the ngrok through the email
Prevention
● Payloads are one of Malwares, so the prevention methods are same
with Malware prevention methods.
● REMEMBER if you have strong antivirus software you are 80% safe.
StegnoGraphy.
● Steganography is the practice of hiding a secret message
inside of (or even on top of) something that is not secret.
● That something can be just about anything you want.
● These days, many examples of steganography involve
embedding a secret piece of text inside of a picture
● But also we can hide inside audio files and etc
● There are many tools for this.
○ The famous on is “steghide”
Keylogging
● Keyloggers are activity-monitoring software programs or
hardware device that give hackers access to your personal
data.
● The passwords and credit card numbers you type, the webpages
you visit – all by logging your keyboard strokes.
● The software is installed on your computer, and records everything
you type.

# The Steps To Get wgel flag
1. we have to open our linux like kali,ubuntu.. or other you used
2. Then open Terminal 
3. open the openvpn we used in Tryhackme
4. Then open the Tryhackme wepsite with your account
5. search for wgel ctf 
6. when the wgel ctf is open start the machine after a 1 min or 60 seconnds and gives as ip adderss then copy ip address
7. go back to new terminal beacuse if you are using virtual machine the openvpn will disconnect so open new terminal
8. put the ip in sudo nano /etc/hosts/ wgel.thm
9. create a Directory to put all ctf you play for now i create TryHackMe then again create directory on TryHackMe wgel
10. first gather information by nmap type nmap -sV -Pn wgel.thm -o nmap result.txt
11. then downloade gobuser
12. use different method but finally we get the user file by typing dirb http://wgel.thm/ then we see /sitemap/.ssh/ when we open this id_rsa written in wepsite form when we open we get some notes so copy it create text file nano id_rsa then past it and save it
13. and write command chmod 600 id_rsa
14. after this write command ssh -i id_rsa jessie@wgel.thm we  get this name from when we gather information search ip on browser the it opens when you go to sourse code some things written unique like in comment  <!-- Jessie don't forget to udate the webiste -->so we use jessie
15. we get in in to jessies account then iuse different commands to get user flag type find . -name "user*" 2>/dev/null
16. when it runs we get different file but on the last there is ./Documents/user_flag.txt then to open i use cat
cat then the path then finally we got users flag


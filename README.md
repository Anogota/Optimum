1. Which version of HttpFileServer is running on TCP port 80?
I did simply scan, to get some information about this HTTP, here is the result:

![obraz](https://github.com/Anogota/Optimum/assets/143951834/ff08e0e6-eb0b-4a21-b767-16e924fe3660)

2. What is the 2014 CVE ID for a remote code execution vulnerability in the findMacroMarker function in HttpFileServer 2.3 version?
Find this vuln is very simple u must copy this version and paste in google and i first link you can see exploit-db and there is the vuln, this is a Remote Code Execution.
Here is a definition of RCE "Remote code execution (RCE) is when an attacker accesses a target computing device and makes changes remotely, no matter where the device is located"

![obraz](https://github.com/Anogota/Optimum/assets/143951834/64d3e685-b587-4408-930c-e6e6dc1a89b7)

3.What user is the webserver running as? Provide the username without the domain.
First what i did is turn on my metasploit i try found this RCE, and i found:

![obraz](https://github.com/Anogota/Optimum/assets/143951834/02017274-0c91-42cd-bb92-1e666b8da8f1)

I have small problem with this exploit, if u have the same problem what i have i mean the exploit don't wanna run, restart your lab this help me, but rember to insert the RHOST and LHOST then write run or exploit
And u will get a meterpreter session, write shell in this meterpreter, to get a shell :P HEH
And also here the answer for 3 question. ![obraz](https://github.com/Anogota/Optimum/assets/143951834/988942fc-d62d-4da6-8bd0-bec18d1fb748)

4.Submit the flag located on the kostas user's desktop.
Here the flag for this user, to take a user flag is was a piece of cake.

![obraz](https://github.com/Anogota/Optimum/assets/143951834/3586447c-0c9d-4f9a-bcc7-fe73ada5dd1c)

Which metasploit reconnaissance module can be used to list possible privilege escalation paths on a compromised system?
I rember this exploit, i used this exploit few labs ago, and found on metasploit.
![obraz](https://github.com/Anogota/Optimum/assets/143951834/7ff1fb26-486b-40b3-9429-c9686dc18f0c)


5. Submit the flag located on the administrator's desktop.
Press CTRL+Z and go to background, when now in metasploit, use this exploit suggerster, and select ur secion, my is 1, then run this exploit.
If your suggester will found something, check this with your metasploit, then when you will find something use this exploit and again select ur session and run this exploit and u will get the Administrator
I can't do this, because this machine is to mutch lagged, i download 2 times new vpn, rester the machine but without result, here is only to step to do it without screanshot but i hope you will do this, pretty simple to do.

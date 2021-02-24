My OSCP Preparation:

This is my experience and I have committed a lot of mistakes and learnt a lot. Although, this was my path to success, I would neither recommend nor stop you from following my path.

My actual plan was to start OSCP preparation from April 2020 after my bachelors (supposed to end in march 2020), but Covid-19 wreaked havoc and I had to change the entire plan from there. I finished my Bachelors in June 2020, and took a little break from everything, wanted to reset my mind from the ugly Covid-19 lockdown effect.

Pre-Exam Preparation:

September

From September I enrolled into a course held by a government institute on cyber security. It stretched from September to November, with a CTF as final test held in December. It was more focused on exploit development and blue team skills, overall, it was a good course. W.R.T its relation to OSCP certification, I would say it was more advanced and dealt mostly about current requirements in the job market.

The Topics covered over 3 months were:

- Reversing Firmware
- Data Encoding
- Malware Focused Network Signature
- Introduction Fuzzing
- Patch Diffing
- One Day Exploit
- ROP
- IEEE Standards
- Indicators of Compromise and Indicators of Attack
- Fail Safe and Fault Tolerant Systems
- SOC Maintenance
- Cryptography Basics
- Number Theory
- Stream Cipher
- Asymmetric Key Cryptography
- Hash Functions, Digital Signature
- File System Forensics - Secure Deletion
- File System Forensics - Data Hiding
- Windows Forensics
- Case Study II and Examples
- Introduction to Reverse Engineering
- Assembly Language Primer
- Reversing Program Binaries Offline
- Reversing API
- Reversing Applications
- Reversing .Net and Decompilation
- Incident Response and Malware Discovery
- Memory Forensics
- Network Forensics
- Database Forensics
- Basics of System Programming
- Basic Kernel Programming
- Android Introduction
- Android Application Component
- Android Malware Identification
- Http Web service
- Ftp and Websockets
- Anonymity using Proxy
- Tor Demo
- ProxyChain Demo
- SQL Injection
- OWASP Top
- XSS
- Burp Suite
- Firefox Add On
- Password Cracking
- Introduction to APT
- Introduction to VAPT
- Overview of Module
- VAPT Essential Tools
- Memory Forensics and Examples
- Case Study III and Case Study IV
- Introduction to Cyber Crime and Cyber Forensics
- Case Study I
- Passive Info Gathering Part
- Active Info Gathering
- Service Enumeration
- Reversing Live Debugging
- Reversing Tools
- Advanced Static Analysis
- Shell Code Analysis
- Anti Reversing Techniques
- Intro Static and Dynamic Malware Analysis
- Packing Unpacking
- Sandboxing
- Advanced Dynamic Analysis Demo
- Practical Offline Code Analysis
- Network Driver Interface Specification
- NDIS Practical Programming
- WMI Programming and PowerShell
- Writing Shell Code
- Software Vuenarbilities Buffer Overflow
- Process Injection DLL Injection API Hooking
- Demo of DLL Injection
- Demo of Hooking
- Business Continuity Plan
- Disaster Recovery Tier 1 2
- Technical Report
- Introduction to Virtual Machines and Hypervisors
- Introduction to Cloud Computing
- Introduction to Cyber Crime, Dark Web, Social Media Threats
- Recovery Partition
- Android and iOS Architecture
- iOS Application Security
- Automated Malware Analysis using Cuckoo Yara
- Rootkits, SSDT, IDT Hooking
- File System Filter Driver
- ARM Assembly Programming
- and Practical
- 64 bit ARM v8 Assembly Programming and Practical
- Linux Exploit Development
- iOS Kernel Debugging
- Advanced Kernel Exploit
- Linux Internals
- Linux Boot Process
- Boot Security
- Windows OS Internals
- Executable File Formats
- Fuzzing using Syzkaller
- Adv Dynamic Analysis Kernel Debugging
- Windows Boot Process
- Windows Boot Process v2
- AV Obfuscation
- Windows Kernel Debugging
- AD Lateral Movement
- File-less Malware 64-bit Malware
- Dynamic API Loading
- Covert Malware Launching
- Full Stack debugging of Android Application
- OOP Analysis
- Stack Overflow Prevention
- SEH Exploit
- ROP Exploit
- KSLR Bypass SMEP Bypass
- BYOD Security
- ASLR Bypass NX Bypass
- Egg Hunting
- Smart Grid
- Secure Socket Layer / Transport Layer Security
- Hands-on class- Wire-shark dump analysis, PCAP analysis
- Intrusion Detection System (IDS/IPS)
- Firewall Configuration
- Attacks- snooping, spoofing
- DPI techniques- practical aspects, traffic reconstruction
- Elliptic Curve Cryptography

Going through all this I felt like a jack of all king of none, I respect the effort put into this by the authors, but this deals with more advanced topics than those required for OSCP, but really helps for OSED preparation. Although I am not interested in exploit dev and Reverse Engineering, this was some real good material and experience to learn some of the advanced techniques of exploitation. Overall, I rate this course at 7/10.

Why I am mentioning about this course is because it has helped me about being able to search on my own about topics I don&#39;t understand or searching for exploits/tutorial on how to exploit. Unfortunately, I can&#39;t share those resources as they are proprietary like Off-sec materials, but it was a good practice for me.

December:

I subscribe to HTB VIP, since I have now set my mind for OSCP certification with lab subscription from January 3rd 2021. I enrolled into HTB tracks, with the thinking that I will approach this lab as a complete beginner with a little experience on being able to understand running basic tools and exploitation. I was pretty comfortable with Linux boxes, but my windows skill sucked, I would say absolute 0 even when it comes to gaining a foothold on windows boxes. My Friend who passed his OSCP in January 2020 had scared me, &quot;OSCP labs are tough, focus on windows, its hard, focus more on foothold (Really important IMO), privilege escalation is really tough, you will get stuck in there&quot;. Now as a person with no experience with windows exploitation, I was really scared, because those words were from a very close friend (he is better than me) who had failed his first attempt by 5 points. I started to work only on windows machine. I bookmarked TJ Null&#39;s [List](https://docs.google.com/spreadsheets/d/1dwSMIAPIam0PuRBkCiDI88pU3yzrqqHkDtBngUHNCw8/edit#gid=1839402159) for OSCP preparation. I just did like 6-7 easy boxes in windows. I found out I sucked very badly when it comes to windows exploitation without Metasploit. So, I shifted focus back on Linux machines to make sure I don&#39;t lose practice. 15 days later I was not at all felling comfortable with either Linux or windows exploitation, I don&#39;t know why, but I was just not able to do the even easy boxes. I got a suggestion from a friend to switch to TryHackMe immediately and enrol in their [Offensive Pentesting](https://tryhackme.com/path/outline/pentesting) path. I subscribed THM from 19th December 2020. Now the difference I found between THM and HTB is mainly the light themed interface (easy navigation and better UIUX), and provision of writeups. THM is really good for beginners and it was a huge morale booster for me. For a guy who sucks at windows, in like 10 days was doing really good at windows exploitation without referring to writeups. I still did not touch buffer overflow in the THM labs. So I get back to HTB on 29th December to test my skill in windows.

I tried retired boxes, I solved the very same boxes which I struggled to complete without Metasploit and this time I felt really good solving windows. I was really happy, I recommend THM before HTB.

Takeaways from THM:

- I got introduced to winpeas, linpeas and autorecon.
- Beautiful introduction to Active Directory, which really helped me solve the AD boxes in OSCP labs without nudges
- Understanding enumeration and reconnaissance.
- It builds confidence before entering the labs.

January:

OSCP lab time:

My subscription was for 60 days, From January 3rd to 4th March.

January 3rd 2021, local time 9 AM I download all materials and connect to Labs.

My initial Plan:

- Finish the Lab report by 2 weeks for the bonus 5 points
- Then finish atleast 2 box a day to stay on target to finish all 66 boxes.
- After labs take HTB VIP and prepare for another month.

I contacted my friend and told him the plan, He said &quot;you won&#39;t be able to get enough lab time later, finish the boxes first. Labs are really hard. Then look at the report&quot;. And I was scared again, what if I don&#39;t get time later to do report, but since he is OSCP pass I though it was better to listen to him than to go on my own path.

I had dedicated my entire time for the labs, I could work up to 10-12 hours a day and would stop doing it when my mom would come and scold me at night like &quot;get to bed its 1AM/2AM&quot;. My routine would be wake up at 10 AM as my younger brother had online class and he would occupy the study room till 12 PM. I would finish my other activities till 12 PM and would sit solving the boxes. Sometimes the practice would go all the way till 3 AM in the morning. I would hardly take breaks, at max 1 hour for lunch and dinner.

So, I started with [PWK Labs learning path](https://help.offensive-security.com/hc/en-us/articles/360050473812) and started with Alpha, I followed the walkthrough and solved it using the same method. Next, I tried Beta, and just looking at the writeup, I don&#39;t know why, it looked hard at that time and skipped it. Next on the path was Alice, sure enough, easy machine, took a little time than what I thought, but got it later. I followed the path for 3 days before taking on other machines.

On the first day, I just did 2 boxes, later I tried Bob after Alice as they are best of friends. 2nd day 6 boxes, 3rd day 3 boxes, 4th day 3 box. 5th day I took the day off to rest a little and work on exercises. 6th day 6 boxes. 7th day I did Gh0st as the only box which took me 3 hours approx. first week, I had 21 boxes of which 8 were Active Directory. AD was simple, if you got 1 box its easy to get the other boxes. To be honest I was really surprised at the result, my friends were also shocked at the rate I was doing. They said I was cheating, looking at hints, etc. I had referred the forums for a couple of box till then, and took nudges for a couple, but majority was on my own. My friends challenged me to do the big 4. I took on sufferance, needed 3 hours again due to the type of exploit and time needed to look at the exploit and understand it. Next was Pain, this was very easy, 2 hours approx from start of recon I had rooted this box. I was really having some great confidence doing these boxes. But at last humble got me stuck on priv esc , that was the first box which extended beyond a day.

About the big 4: (My learning)

- Gh0st: teaches you how to enumerate and not blindly trust what you see, it teaches you to verify your findings.
- Pain: Teaches you to keep it plain and simple.
- Sufferance: It teaches you how to configure your system on the go and how to google the exploits
- Humble: Patience and never give up attitude.

There are boxes more difficult than the big 4, but if your enum is correct, you will get them easily.

January 23rd box number 52 done. By this time, I had pivoted into all other networks after unlocking them. 25th was the last box I did (53rd). I stopped there for a break as the continuous stretch with little break and erratic sleep cycle started to affect my health. And that was the last time I connected my lab VPN before starting with Buffer overflow on 17th February.

February:

I am still lazy to connect to labs for practice and felt the labs were repetitive (like sometimes just a port scan was all it needed to know the port to attack and exploit) and the systems were having some old exploits. But by this time I was really comfortable with autorecon, mass scan, winpeas, linpeas, socat, port forwarding, sshuttle, tunneling. I was happy that I don&#39;t need Metasploit for most exploits as I was cruising with EDB and google.

I had made very good friends in [InfoSec Prep](https://discord.gg/Dk8kM4SX) Discord server. We were going on together as study partners helping each other when stuck and sharing techniques. I learnt a lot of different tools and approach while in the server. So I took PG practice from 5th started doing working on windows boxes. And in 5 days I was done with 12 boxes. Really high with confidence

February 10th: A friend of mine had scheduled his exam, Well, he failed. Now this started giving me some worries. He said he could get 35 points after using Metasploit. This was buf + a 10-pointer machine.

February 16th around midnight:

A study partner asked me when I was planning to give my exam, so I said I planned to schedule it on march 4th, but he said dates are booked till 14th March, I verified the same, I had either 18th ,19th, 21st or on March 15th. I was angry on my stupidity of not scheduling before, I call my friend in the middle of night, I say I am confident but don&#39;t have any clue about buffer overflow. I have 4 days left, I said I will try for two days, if I don&#39;t get it, then I will reschedule the exam, If I fail it would be the biggest gamble and stupid thing I ever did. In 5 min I decided to schedule the exam on 21st February 7-30 AM local time. And the next day started buffer overflow practice

I had another friend giving his exam on 17th February, both of us had full confidence he was going to pass given his experience and ranks in HTB. He was by all means better than me. But I get the message he failed by 5 points. I was shocked, like a guy who is so good failed, did I make a mistake of scheduling it so early with no proper preparation. I had a lot of confidence as I was able to solve PG practice intermediate and hard rating machine (as per community votes) in 1.5 – 2.5 hours. But I started lab Buffer overflow, got it in like 4 hours, did another buffer overflow exercise in lab. Felt pretty good, and I felt like I panicked for no reason. Next day I did [THM Tib3rius](https://tryhackme.com/room/bufferoverflowprep) buffer overflow room and I was doing each exercise in 15 min max. Now felt I&#39;m all good for exam. Next two days just did a couple of PG practice linux box. And on 20th February I took snapshot of my VM, got my notes arranged. All set for exam. But the excitement and erratic sleep cycle dint let me sleep till 2-30 AM, I had like at max 4 hours sleep before exam.

Exam Day:

Exam starts at 7-30 AM, I sleep at 2-30 AM, wake up at 6-45 AM, Freshen up, at 7 AM I login to THM , and practice buffer overflow exercise 10 one last time. By 7-20 I login and start the verification steps. My webcam gave issues during ID verification, so the verification ends at 7-40 AM.

My initial Plan:

- 25 points buffer overflow in 1 hour with writeup
- Manually run mass scan and do a nmap scan based on the mass scan output.
- Run autorecon before the start of buffer overflow
- Start on 20 pointers
- Based on time and recon choose the next box.

Nothing went according to the plan, call me over confident, I don&#39;t have a backup plan.

Here is what happened:

- I directly started buffer overflow, 5 min after start I realize I dint start my scan.
- Went back to scan, The mass scan and nmap took 10 min for the 4 boxes
- Its 8 AM, autorecon starts, in the panic mode I failed to scan one target, and the nmap for the failed target was the same as another box.
- In this situation I screw my buffer overflow box, had to reset it, 2 hours after start I get the buffer overflow.
- My scans a little messed up, took half an hour to sort it out, Till this time, I had not eaten anything, and morning time its all disturbance by neighbours, road sweepers, barking dogs, what not.
- I thought I was gonna fail. Nothing is going properly, all messed up.
- I decide to take a break , its roughly 10 AM, eat breakfast, calm myself down and back in lab at 10-30 AM.
- I ask the proctor if I can play music, which the proctor agreed to. Now I made up mind stating, this is not exam , you are working on lab machines , u have music which lets u concentrate like in labs. I got marshmello music up. And started again.
- 30 min in I get a low priv shell on a 20 pointer. Start running the \*peas, not much details, I do some manual searching. I feel I have the correct exploit for priv esc. I got the exploit inside the target. Dint work, tried other, dint work. An hour gone, have 35 points. I decide to take a break for 10 min
- I come back, enum on the other 20 points, nothing for a foothold also
- Switch to 25 pointer, This is where the recon skills from lab , Gh0st and Sufferance came into use, just googled what I saw, got a link to an exploit, ran it, got shell. Took a break again to calm down. Easy priv esc and got 25 points. Break again. All I need is 10 more points to pass
- Switch to 10 pointer, Gh0st and Sufferance again helped me in the technique here to get the exploit and get the shell
- 7 hours and 40 min from start of exam in I have 70 points. 4 hours from the point I thought I fail, I have the passing points. I am really happy, took break to celebrate in the house.
- I get to taking screenshot and reporting, I finish a draft copy by 6 PM of all 4 boxes.
- I switch focus on the priv esc on the 20 pointer, no luck, 10-30 PM, I&#39;m tired and feel like out of options and quit the exam with 70 points.

Done with exam, now only reporting left, the anxiety, stress and lack of sleep has me really down, next day I finish report and submit it I fell sick with headache cold and sore throat. I&#39;m still scared what if I made a mistake in the report, I don&#39;t have extra marks, what if I fail, etc. 24 hours after submission, I receive a mail, I passed in the first attempt in spite of all the stupidity and gamble I took before the exam

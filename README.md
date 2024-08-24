# Information Security Knowledge, Training, and Educational Resources

Welcome to my repository of resources to help the budding information security professional round out their knowledge-base on tools, training and education around our industry. I hope you find this information useful. Please feel free to fork this and add to it if you think something is missing here. Please see the [wiki](https://github.com/djchateau/ISKTER/wiki) for this project for details on the pull request process. My only expectations on these lists is that the resource added has been vetted for quality and is something you've personally used and found benefit from at some point or another. What I don't want to is to fill this with resources that are either dead, have no relevancy or just become another dead pile of links that will serve no one. 


## Reading List informing the “Why?”

- [C Programming Language, 2nd Edition](https://www.amazon.com/Programming-Language-2nd-Brian-Kernighan/dp/0131103628/) by Brian W. Kernighan & Dennis M. Ritchie
- [Countdown to Zero Day: Stuxnet and the Launch of the World's First Digital Weapon](https://www.amazon.com/Countdown-Zero-Day-Stuxnet-Digital/dp/0770436196/) by Kim Zetter
- [Cracking the Coding Interview: 189 Programming Questions and Solutions (Cracking the Interview & Career), 6th Edition](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850/) by Gayle Laakmann McDowell 
- [Cyber War: The Next Threat to National Security and What to Do About It](https://www.amazon.com/Cyber-War-Threat-National-Security/dp/0061962244/) by Richard Knake and Robert Clarke
- [The Cuckoo’s Egg: Tracking a Spy Through the Maze of Computer Espionage](https://www.amazon.com/Cuckoos-Egg-Tracking-Computer-Espionage/dp/1416507787/) by Cliff Stoll
- [Dark Territory: The Secret History of Cyber War](https://www.amazon.com/Dark-Territory-Secret-History-Cyber/dp/1476763267/) by Fred Kaplan
- [Dawn of the Code War: America's Battle Against Russia, China, and the Rising Global Cyber Threat](https://www.amazon.com/Dawn-of-Code-War-audiobook/dp/B07J9L41HH/) by John Carlin
- [The Perfect Weapon: War, Sabotage, and Fear in the Cyber Age](https://www.amazon.com/Perfect-Weapon-Sabotage-Fear-Cyber/dp/0451497902/) by David Sanger
- [Sandworm: A New Era of Cyberwar and the Hunt for the Kremlin's Most Dangerous Hackers](https://www.amazon.com/Sandworm-Cyberwar-Kremlins-Dangerous-Hackers/dp/0525564632/) by Andy Greenberg

### Networking and Cybersecurity Concepts:

- [Hacking: The Art of Exploitation, 2nd Edition](https://www.amazon.com/Hacking-Art-Exploitation-Jon-Erickson/dp/1593271441/) by Jon Erickson

## Tools

### Multi-Use

- [CyberChef](https://github.com/gchq/CyberChef): Self-described as the "Cyber Swiss Army Knife" created and maintained by UK's four-letter glowies, it contains an impressive amount of functionality for doing analysis and assisting in other cybersecurity-related work and activities, such as CTFs.


### Home Labs

- [GOAD (Game of Active Directory](https://github.com/Orange-Cyberdefense/GOAD): GOAD is a pentest active directory LAB project. The purpose of this lab is to give pentesters a vulnerable Active directory environment ready to use to practice usual attack techniques.
- [Microsoft Activation Scripts (MAS)](https://massgrave.dev/): A Windows and Office activator using HWID/Ohook/KMS38/Online KMS activation methods, with a focus on open-source code and fewer antivirus detections.

### Enumeration

#### Users

- [Finger User Enumeration Script](https://github.com/pentestmonkey/finger-user-enum): Username guessing tool primarily for use against the default Solaris finger service. Also supports relaying of queries through another finger server.

#### Network

- [AutoRecon](https://github.com/Tib3rius/AutoRecon): AutoRecon is a multi-threaded network reconnaissance tool which performs automated enumeration of services.
- [impacket](https://github.com/fortra/impacket): Impacket is a collection of Python3 classes focused on providing access to network packets. Impacket is highly effective when used in conjunction with a packet capture utility or package such as Pcapy. 
- [nmap](https://github.com/nmap/nmap): A comprehensive network mapping and enumeration tool with scripting extensibility.
- [WhatWeb](https://github.com/urbanadventurer/WhatWeb): Scans and identifies software/services used on a given target website.

#### Privilege Escalation

- [peass-ng](https://github.com/peass-ng/PEASS-ng): These tools search for possible local privilege escalation paths that you could exploit and print them to you with nice colors so you can recognize the misconfigurations easily.


### Reverse-Engineering

- [de4js](https://de4js.kshift.me/): A JavaScript deobfuscator.
- [Ghidra](https://github.com/NationalSecurityAgency/ghidra): A software reverse-engineering framework created and maintained by everyone's favorite glowies, the NSA.
- [jd-gui](https://github.com/java-decompiler/jd-gui): A Java decompiler.
- [pwntools](https://github.com/Gallopsled/pwntools): A Python CTF framework and binary exploitation library.

### Useful Browser Extensions

- [FoxyProxy](https://getfoxyproxy.org/): A browser extension for quickly switching proxy configurations in your web browser during an engagement.
- [Hack Tools](https://github.com/LasCC/HackTools): Provides a wide-variety of payloads and other useful shell commands you can use during an engagement.
- [Livemarks](https://github.com/nt1m/livemarks/): A RSS Feed reader uses your bookmarks folders to maintain RSS feeds you provide it.
- [Multi-Account Containers](https://github.com/mozilla/multi-account-containers)
- [Search By Image](https://addons.mozilla.org/en-US/firefox/addon/search_by_image/): A powerful reverse image search tool, with support for various search engines, such as Google, Bing, Yandex, Baidu and TinEye.
- [uBlock Origin](https://github.com/gorhill/uBlock#ublock-origin): The go-to when it comes to ad-blocking while being CPU-performant.
- [User Agent Switcher and Manager](https://webextension.org/listing/useragent-switcher.html): A versatile user agent switcher.
- [vimium](https://github.com/philc/vimium): It's not enough to have vim in your terminal. Show your browser some love by putting vim motions into your browser too.

## Practice

### Coding

- [Advent of Code](https://adventofcode.com/)
- [Exercism](https://exercism.org/tracks/c/)
- [LeetCode](https://leetcode.com/problemset/all/)
- [Socket Programming Bible](https://beej.us/guide/bgnet/)

## Online University/Course Material

- [15-410, Operating System Design and Implementation](https://www.cs.cmu.edu/~410/)
- [Nightmare](https://guyinatuxedo.github.io/index.html): A self-paced course covering binary exploitation and reverse engineering.
- [Binary Exploitation](https://ir0nstone.gitbook.io/notes/): A self-paced course covering binary exploitation.
- [Computation Structures: Procedures and Stacks](https://computationstructures.org/lectures/stacks/stacks.html)
- [Cornell ECE Open Courseware](https://ocw.ece.cornell.edu/)
- [Operating System Engineering](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-828-operating-system-engineering-fall-2012/)
- [pwntools Tutorial](https://github.com/Gallopsled/pwntools-tutorial): A fantastic python module to know for binary exploitation purposes. 
- [Virtual Memory](https://www.cs.uic.edu/~jbell/CourseNotes/OperatingSystems/9_VirtualMemory.html)

## Binary Exploitation

- [Ghidra Class](https://github.com/NationalSecurityAgency/ghidra/tree/master/GhidraDocs/GhidraClass): Within the documentation of the Ghidra software has class material for helping teaching how to use the software.
- [PicoCTF (binary exploit and RE)](https://picoctf.com/)
- [ROP Emporium](https://ropemporium.com/index.html): Challenges intended to help teach you about Return-Oriented Programming.

### Challenges

- [Exploit Education: Phoenix](https://exploit.education/phoenix/)
- [OverTheWire: Vortex](https://overthewire.org/wargames/vortex/vortex0.html)
- [pwn.college](https://pwn.college)

## Capture the Flags (CTF)

- [ångstromCTF](https://angstromctf.com/)
- [CyberStakes](https://www.acictf.com/)
- [MetaCTF Competition](https://app.metactf.com/): Great CTF for a short CTF to flex your muscle on.
- [picoCTF](https://picoctf.com/)
- [HSCTF](https://hsctf.com/)
- [Life of Binaries](https://opensecuritytraining.info/LifeOfBinaries.html)
- [PACTF](https://pactf.com/)[^1]
- [PPP](https://zaratec.io/ctf-practice/)
- [OverTheWire](https://overthewire.org/wargames/): Great beginner platform for those looking to getting into CTFs to practice on Linux boxes, particularly their Bandit server.
- [RPISEC](https://github.com/RPISEC/MBE/tree/master)
- [UnderTheWire](https://underthewire.tech/wargames)

### Classes

- [CWA-67 Cyber Competition Team (CCT) Discord](https://discord.gg/vJd6HCnVNB)

## Documentation

### Text Editors

- [vim](https://www.vim.org/): Included in most Linux and Unix-like operating systems by default, vim is a lightweight, yet powerful, modal text editor that can be easily used in your terminal or through and SSH and tmux and is highly extensible. It is available on most operating systems.

### Note-Taking

- [Obsidian](https://obsidian.md/): Note-taking application available on both desktop and mobile using Markdown and a diverse array of community plugins to customize your note-taking to your workflow. Because everything is stored in Markdown and stored locally, it can make transforming your notes into reports that you may need to generate down the road.

### Reporting

- [Dradis CE](https://dradis.com/ce/)
- [SysReptor](https://github.com/syslifters/sysreptor/): A fully customisable, offensive security reporting solution designed for pentesters, red teamers and other security-related people. Easy report writing using Markdown, HTML and CSS that can be converted into a clean looking PDF. Open-source and self-hosting options are available.

## Community/Discussion

- **Discord:**
  - [CryptoHack](https://discord.gg/h9E7cna5pV)
  - [Dead Pixel Sec](https://discord.com/invite/deadpixelsec)
  - [OpenToAll](https://discord.gg/saVj85jjFy)
  - [picoCTF](https://picoctf.org/discord)
  - [Reverse Engineering](https://discord.com/invite/rtfm)
  - [Rhino Security Labs](https://discord.gg/xFXmqytprV)
- **Reddit:**
  - [/r/LiveOverflow](https://www.reddit.com/r/LiveOverflow/)
  - [/r/securityCTF](https://www.reddit.com/r/securityCTF/)

## Content Creators/Streamers

- [InfoSecStreams](https://infosecstreams.com/): An actively maintained activity-based-autosorted list of Information Security streamers.
- [Security Creators](https://securitycreators.video/): Similar to InfoSec streams, but a more curated list of content creators.

### Notable Creators/Streamers

- [DJ Chateau](https://www.twitch.tv/dj_chateau): Ok, sure. I'm tooting my own horn here, but I stream on Twitch pretty regularly doing boxes from platforms like TryHackMe, HackTheBox, and react to and discuss various information security topics.
- [John Hammand](https://www.youtube.com/c/JohnHammond010/playlists): Security researcher at Huntress with a large following and a solid number of videos going over various security news, CTFs and other platforms like TryHack and HackTheBox.
- [LiveOverflow](https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN): LiveOverflow has an excellent array of videos on binary exploitation and reverse-engineering that are worth going through.
- [Tib3rius](https://www.youtube.com/@Tib3rius): Well-known web application pentester and creator of [AutoRecon](https://github.com/Tib3rius/AutoRecon).

### Podcasts

- [CTF Radiooo](https://www.youtube.com/channel/UC-aOX0H7RXOrxzzJjWb17lg)
- [Darknet Diaries](https://darknetdiaries.com/)
- [Security Chipmunks](https://securitychipmunks.com/)[^2]
- [Unsecurity](https://frsecure.com/unsecurity/)

## News Aggregation

### RSS Feeds

- [/dev/random/](blog.rootshell.be/feed)[^3]
- [AWS Security Blog](https://aws.amazon.com/blogs/security/feed/)
- [Bishop Fox Blog](https://bishopfox.com/feeds/blog.rss)
- [Black Hills Information Security](https://www.blackhillsinfosec.com/feed/)
- [Bleeping Computer](https://www.bleepingcomputer.com/feed/)
- [CISA News](https://www.cisa.gov/news.xml)
- [CISA Blog](https://www.cisa.gov/blog.xml)
- [CISA Advisories (All)](https://www.cisa.gov/cybersecurity-advisories/all.xml)
- [Crowdstrike Blog](https://www.crowdstrike.com/blog/feed)
- [Expression with Curiosity: Security Lesson Bytes](https://maybelynplecic.substack.com/feed?sectionId=123773)
- [MetaCTF Announcements](https://metactf.com/blog/tag/announcements/feed/)
- [Hacker News](https://news.ycombinator.com/rss)
- [Hacking Articles](http://hackingarticles.in/feed)
- [HackTheBox  Blog (All Content)](https://www.hackthebox.com/rss/blog/all)
- [Impose Cost](https://www.imposecost.net/blog-feed.xml)
- [IT Security Guru](https://www.itsecurityguru.org/feed/)
- [Krebs on Security](https://krebsonsecurity.com/feed/)
- [Sentinel One Blog](https://www.sentinelone.com/blog/feed/)
- [Schneir on Security](https://www.schneier.com/feed/atom/)
- [The Hacker News](https://feeds.feedburner.com/TheHackersNews)
- [Troy Hunt's Blog](https://www.itsecurityguru.org/feed/)


[^1]: Has not been run since 2019.
[^2]: Last episode appears to been posted in April 2022, but still worth listening through the available episodes.
[^3]: Last feed update was back in October 2023, but still lots of useful information here.

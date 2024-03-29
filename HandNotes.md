# CompTIA Security+ SY0-601
## 1.1
### Phishing
- Typosquatting
    - URL Hijacking
    - Prepending
- Pretexting: *Lying*
- Pharming: *Attacking a group of people*
- Redirection: *Legit website -> Bogus website (Poisoned DNS, client vulnurabilities)*
- By Redirection Combining Pharming & Phishing
    - **Pharming**: *Harvest large groups of people*
    - **Phishing**: *Collect access credentials*
- Difficult for anti-malware
    - Everything appears legitimate
- **Vishing (Voice Phishing)**
    - Spoofing
    - Fake security checks, bank updates
- **Smishing (SMS Phishing)**
    - Spoofing
    - Forward links, asks for personal info
- Variations:
    - Fake check scam
    - Phone verification code scam
    - Boss/CEO scam
    - Advance-fee scam
- Reconnaaissance
- Background Info
    - Lead generation sites
    - Facebook, Twitter etc.
    - Corporate websites  

    With the info collected, attackers build a beliavable pretext:  
    - Where you live
    - Where you work
    - Where you bank
    - Recent transctions
    - Family and friends
- **Spear Phishing**: *Targeted phishing with inside info*
- **Whaling**: *Targeted (spear) phishing with the possibility of a large catch like CEO, CFO*

### Impersonation
- The Pretext
- **Impersonation**: *Attackers pretend to be someone they aren't*
    - Use the details from recon
    - Attack someone with a higher rank
    - Throw tons of technical details around
    - Be friendly
- **Eliciting Information**: *Extracting info*
    - The victim doesn't even realize
    - Often seen with Vishing
    - Well documented psychological techniques
- **Identity Fraud**
    - Your identity can be used by others
- **Credit Card Fraud**: Opening an account in your name or using your credit card info
- **Bank Fraud**: Attackers gain acces to your account or open a new one
- **Loan Fraud**: Your info is used for a loan or lease
- **Government Benefits Fraud**
- Protecting your info
    - Never volunteer info
    - Don't disclose personal details
    - Always verify, by a 3rd party etc

### Dumpster Diving
- Garbage bin
- A very effective way to get useful info
- Legal in the US
- If it's in garbage then nobody owns it
- Protect your rubbish
    - Fence and lock
    - Shred docs
    - Governments burn good stuff

### Shoulder Surfing
- Simply looking over your shoulder to your screen or your keyboard while typing
- Curiosity, industrial espionage, competitive advantage
- Easy to do:
    - Airports, Flights
    - Hallway-facing monitors
    - Coffee shops
    - Binoculars, telescopes
    - Webcam monitoring
- Preventing:
    - Be aware of surroundings
    - Use privacy filters: *blacks side vision*
    - Keep the monitor out of sight like hallways or windows

### Hoaxes
- **Hoax**: A threat that doesn't actually exist!
- Consumes lots of resources
    - Forwarded messages, printed memorandums...
    - Often an email, or facebook post etc.
- Some hoaxes will take money
- A hoax about a virus (makes you believe you are infected) can waste as much time as a regular virus
- De-hoaxing
    - It's the Internet, believe no one
    - Consider the source
    - Cross reference:
        - https://hoax-slayer.net
        - https://snopes.com
    - Spam filters can help
    - If it sounds too good to be true...

### Watering Hole Attacks
- What if the network is totally secure?
    - Can't plug in USB
    - Can't open attachments
    - Can't click open links
- As a response attackers developed a new way:
    - **Watering Hole**: The third party that attackers await you/your employees to visit and get infected
    - Determine which website victims go:
        - Educated guess: Coffe shops etc.
        - Industry related sites
- An example of a water hole attack:
    - Jan 2017: Just infected specific IPs like banks etc.
- Watching the water hole:
    - **Defense-in-depth**: Layered defense
    - Firewalls and IPS
    - Anti-virus/malware signature updates

### Spam
- Unsolicited messages; better to stop before it reachers the user's mail box
- Emails, forums etc.
- **SPIM**: Spam over Instant Messaging
- Various content:
    - Ad
    - Non-commercial
    - Phishing attempts
- Significant technology issue:
    - Security concerns
    - Resource utilization
    - Storage costs
    - Managing the spam
- Mail gateways: <br><img src="https://i.ibb.co/xHFpcDk/Mail-Gateway.png">
    - Stop it at the gateway before it reaches the user
    - On-site or cloud-based
- Identifying spam:
    1. **Allowed list**
    1. **SMTP standatds checking**: *Block anything that doesn't follow RFC standards*
    1. **rDNS - reverse DNS**: *Block email where the sender's domain doesn't match the IP*
    1. **Tarpitting**: *Intentionally slow down the server conversation*
    1. **Recipient filtering**: *Block mails not adressed to a valid recipient email address*

### Influence Campaigns
- Hacking public opinion
- **Influence campaigns**: Sway public opinion on political and social issues
- **Nation-state actors**: Divide, distract and persuade
- **Advertising**: Buy a voice
- **Social media**: Creating, sharing, liking; amplification
- Influencing Process: <br><img src="https://i.ibb.co/M6QP6M1/The-Influencing-Process.png">
- Hybrid Warfare:
    - Military strategy
    - Cyberwarfare: *Attack an entity with technology*
    - Influencing foreign election
    - "Fake news"

### Other Social Engineering Attacks
- **Tailgating**: Use an authorized person to gain authorized access
    - 3rd party with a legitimate reason
    - Once inside, little to stop
- Preventing:
    - Visitor policy: Identifying anyone, like via badges and/or giving someone part of the organization with them
    - One scan, one person
    - Access Control Vestibule / Airlock
    - Don't be afraid to ask
- **Invoice Scams**
    - Starts with a bit of spear phishing; attackers know who pays the bills
    - Attacker sends a fake invoice; domain renewal, toner cartridges etc. from: address is a spoofed version of the CEO
    - Accounting pays the invoice by skipping regular checks coz it was from the CEO after all
    - Might also include a pay-link
- **Credential Harvesting**
    - Collecting local passwords
    - Victim receives an email with a malicious Word doc etc
    - Once the macro runs it collects stored credentials and sends to the attacker
    - User has no idea, everything happens in the background
    - Anti-virus/malware can detect and prevent!

### Principles of Social Engineering
- Constantly changing
- May involve multiple people
- May be in person or electronic
    - Phone calls from an aggressive "customer"
    - Funeral notification of a friend or associate
1. **Authority**
    - Attacker seems to be in charge, has authority
1. **Intimidation**
    - If no help, then trouble
1. **Consensus/Social Proof**
    - Convince based on the expected
    - Your co-worker has done this last week
1. **Scarcity**
    - The situation won't be this way too long
    - Take action before time expires
1. **Urgency**
    - Works alongside Scarcity
    - Act quickly, don't think
1. **Familiarity/Liking**
    - Someone you know; we have common friends
1. **Trust**
    - Someone who is safe like from IT, help desk etc.

## 1.2
### An Overview of Malware
- **Malware**: *Malicious Software*
- Gather info
- Key strokes, screenshots
- Participate in a group and controlled over 'net
- Show you ads, attacker makes big money
- Viruses and worms
    - Encrypt all your data; you should pay the attacker to get the decryption key
- Malware types and methods:
    1. Viruses
    1. Crypto-malware
    1. Ransomware
    1. Worms
    1. Trojan Horse
    1. Rootkit
    1. Keylogger
    1. Adware/Spyware
    1. Botnet
- How get infected:
    - A worm gets in via a vulnerability
    - Installs malware for a remote backdoor access
    - Bot may be installed later
- What to do:
    - Don't click links *(inside of an email especially)*
    - Web page pop-up
    - Drive-by download
    - Worm
    - Keep the OS up-to-date
    - Keep the apps up-to-date

### Malware Types
1. Virus
- Malware that can replicate it self
> It needs the user to execute a program to start the replicaton process!
- Can use **the OS** or **the Network** to replicate itself
- May or may not cause problems
- Anti-virus is benefical
- Keep the signatures of anti-virus updated
- Types of viruses:
   1. **Program Viruses**: They are part of the app
   2. **Boot Sector Viruses**: Exist in the boot secture
   3. **Script Viruses**: OS or browser-based
   4. **Macro Viruses**: Runs inside of an app, *common in Microsoft Office*
   5. **Fileless Virus**: Never loads it as a file onto the system. 
   - A stealth attack.
   - Does a good job of avoiding anti-virus detection
   - Operates solely in memory
   - Never installed in a file or app<br>
   <img src="https://i.ibb.co/mv6c1dH/Fileless-Virus.png">

2. Worm
- Malware that self-replicates
> Doesn't need your interaction to run!
- Uses network as a transmission medium
- Self-propagades and spread quickly
- Can take over systems very quickly
- Firewalls and IDS/IPS can mitigate many worm infestations; doesn't help much though once the worm is inside<br><img src="https://i.ibb.co/pnvmy6T/Wannacry-Worm.png">

3. Ransomware
- The data is valuable:
    - Personal
    - Organizational *(PII:Personally Identifiable Information)*
    - Financial info
- The type of getting your data away and requiring you to pay to get back the data called as **Ransomware**
- May be a fake hoax also *(locked by police etc)*
- Just blocks you to reaching the data by an interface
- Denies access to a computer system or data until a ransom is paid.
- It can be removed by security professionals

4. Crypto-malware
- A new generation of ransomware
- A malicious program that encrypts programs and files on the computer in order to extort money from the user.
- Your data is now really unavailable until you pay
- Untraceable payment system
- An unfortunate use of public-key cryptography

- Protecting:
    - Always have an offline backup
    - Keep the OS updated
    - Keep the apps updated
    - Keep anti-virus signatures updated

5. Trojan
- Software that pretends to be something else, so it can conquer the computer
- Doesn't care about replicating
- Circumvents existing security
- Better ones avoid and disable AV
- Once inside, it has free reign and open the doors to additional malwares
- **PUP (Potentially Unwanted Program)**: One type of software commonly downloaded
    - Identified by AV
    - May not be malicious but undesirable
    - Often installed along with other software
- PUP Examples:    
    - Overly aggresive browser toolbar
    - A backup utility that displays ads
    - Browser search engine hijacker
    <br><br>
    ***Backdoors:***
<br>- Backdoors are the rear gates opened by malwares
<br>- Once a backdoor is opened it is used by multiple types of malwares
<br>- Some softwares include a backdoor; *old linux kernel, some bad software*

6. RATs *(Remote Access Trojans)*
- Remote administration tool
- The ultimate backdoor
- Malware installs the server/service/host
- Control a device:
    - Key logging
    - Screenshots/records taking
    - Copy files
    - Embed more malware
- Protecting
    - Don't run an unknown software
    - Keep everything updated
    - Have a backup

7. Rootkits
- Originally a Unix technique
- Modifies core system files, part of the kernel
- Can be invisible to OS, won't see in task manager
- Also invisible to AV
- Rootkits are generally combined with a malware
    > Zeus/Zbot malware + Necrus rootkit (kernel-level driver)
    - Zeus/Zbot famous for cleaning bank accounts
    - Necrus makes sure you can't delete Zeus or even cannot stop the process
- Finding and removing rootkits:
    - Some AV/AM that can identify rootkits
    - Use a specific rootkit remover
    - **Secure boot with UEFI**: This option will look for any changed part in the kernel and not run that part so can prevent rootkits

8.  1. Adware
    - Everywhere ad, pop-up with pop-up
    - May cause performance issues
    - Installed accidentally, may be included with other software installations
    - Be careful about softwares that claims to remove hardware, especially if learned via a pop-up, coz it may be itself an adware.
    <br><br>
    2. Spyware
    - Spyware spies on you; ads, inedtity theft, affiliate fraud
    - Can trick into installing, peer to peer, fake security software
    - Browser tracking
    - Keylogging
    <br><br>
    - There are lots of malwares and adwares because:
        - Money
        - Your seeing is valuable
        - Your computer time and bandwith valuable
        - Your bank account is valuable
    - Protecting:
        - Up-to-date AV/AM
        - Know what you're installing
        - Backup
        - Run some scans; ***Malwarebytes***

9.  1. Bots
    - Robots
    - Once infected then PC is a bot
    - Via Trojan horse, run a program seems to be legit, OS or app vulnerability
    - A day of a bot:
        - Sit around
        - Check with the Command and Control (C&C) server
        - Wait for instructions
    2. Botnets
    - A group of bots working together
    - Their expected actions:
        - **Distributed Denial of Service (DDoS)**
        - Relay spam
        - Proxy network traffic
        - Distributed computing tasks
        - May be rented
    - Live botnet map: <br><img src="https://i.ibb.co/CKv65wJ/Live-Botnet-Map.png"><br>https://map.lookingglasscyber.com/
    <br><br>
    - Stopping the bot:
        - Prevent the initial infection, *via OS patches and AV signature updates*
        - Identifying an existing infection, *on-deman scans, netwok monitoring*
        - Prevent command and control, *block at the firewall, identify at the workstation with a host-based firewall or host-based IPS*

### Logic Bombs
- A logic bomb attack occurs when a seperate event occures.
- Waits for a predefined event:
    - **Time bomb**
    - **User event**
- Difficult to identify
- Difficult to recover if it goes off, because most of the logic bombs deletes itself after being executed.
- Two examples:
    - South Korea, 2013: Deleting master boot records and rebooting systems
    - Kiev, Ukraine, 2016: Disabling electrical circuits. Costumized for SCADA *(Supervisory Control and Data Acquisition)* networks
- Preventing:
    - Difficult to recognize
    - No predefined signatures
    - **Formal change control:** *Checking if any unplanned changes are made within the system*
    - **Electronical monitoring:** *Alert on changes, host-based intrusion detection, Tripwire etc.*
    - **Constant auding:** *An administrator can circumvent existing systems*

### Password Attacks
- Attackers love the apps that store passwords as a plaintext
- Do not store passwords as plaintext!
- If an app detected like this, stop using it.
- **Hashing a password**:
    - Hashes represent data as a fixed-length string of text; *a message digest or fingerprint*
    - Hashes will not have a collision, they are all unique for different inputs
    > Hashing is a one-way trip! Impossible to recover the original message from the digest.
    - **SHA-256 hash** i.e.; *used in many apps*<br><img src="https://i.ibb.co/jwLfyWL/SHA256.png">
    - A sample password file:<br><img src="https://i.ibb.co/h9SxkHP/Password-File.png" alt="Password-File">
1. **Spraying Attack**:
    - Instead of brute forcing the hash to determine what the original password might have been some attacker use spraying attack.
    - A spraying attack avoids the results of a locked account caused by trying the wrong password over and over again. He simply just tries as times to prevent locking out, like 2 or 3 times.
    - There are most commonly used passwords: https://en.wikipedia.org/wiki/List_of_the_most_common_passwords
    - Attack an account with the top three (or more) passwords; *if no success move to the next user; no lockouts, no alarms, no alerts*
2. **Brute Force Attack**
    - Try every possible combination
    - This might take time
    - Until the hashes are matched...
    1. Brute Force - Online
        - Keep trying the login process
        - Very slow
        - Most accounts will lockout after a number of failed attempts
    2. Brute Force - Offline
        - Obtain the list of users and hashes
        - Calculate a password hash, compere it to a stored hash
        - Large computaitonal resource required
3. **Dictionary Attack**
    - Instead of going through every possible combination of letters and numbers, attacker uses a dictionary to try common words.
    - Many common wordlists are available online, customized by language or line of work
    - The password crackers can substitude letters
    - **Distributed cracking**: *Multiple systems used for calculations*
    - **GPU cracking**: *The power of GPUs are used for calculations*
- **Rainbow Table**: A database where all tried hashees are stored to be used in the future. A database contains a massive number of hashes that created earlier.
    - Remarkable speed increase
    - Need different tables for different hashing methods
- **Adding some *salt***:
    - **Salt**: Random data added to a password when hashing
    - Every user gets their own random salt; it is commonly stored with the password
    - Rainbow tables won't work with **salted hashes**
    - Slows things down however won't stop reverse engineering<br><img src="https://i.ibb.co/NrnH6SR/Salted-Hash.png" alt="Salted-Hash">
- When the hashes get out:<br><img src="https://i.ibb.co/nQ6HrMH/When-hashes-get-out.png" alt="When-hashes-get-out">https://haveibeenpwned.com/

### Physical Attacks
1. Malicious USB Cable
    - Looks like a normal one but has additional electronics inside
    - OS identifies it as **HID (Human Interface Device)** like keyboard, mouse.
    - A HID doesn't require any additional permissions
    - Once connected it takes over and may start downloading malware
    - So don't just plug in any USB cable
2. Malicious Flash Drive
    - Especially be careful about free ones!
    - May seem or even function as a normal flash drive
    - Older OSs would automatically run files on a flash drive but this is disabled or removed by default
    - However it may introuduce itself as HID like the malicious USB cable
    - Doing so, it may start a command prompt and type anything without your intervention
    - Attacker might put malware inside the files you've put on the flash drive
    - Can be configured as a boot device and after a reboot it may infect the system
    - Acts as an Ethernet adapter:
        - Redirects or modifies Internet traffic requests
        - Acts as a wireless gateway for other devices
        - So attacker can use your PC as a jump point to your internal network
3. Skimming
    - Stealing credit card information usually during a normal transaction
        - Copy data from the magnetic stripe
        - Or from the computer system that the card is plugged into
    1. ATM Skimming
        - Includes a small camera that watches your PIN
        - Always check card reader closely before using!
    2. Card Cloning
        - Create a duplicate of the card looks and feels like original
        - Can only be used with the stripe; the chip cannot be cloned!
        - Cloned gift cards are common; so once it's activated attacker uses it before the legitimate user

### Adversarial Artificial Inteligence
- Machine learning
- Requires tons of data
- But once trained can capture or prevent lots of undesired situations or do amazing things
- Poisoning the training data:
    - Confuse the AI
    - Attacker sends modified training data that causes AI to behave incorrectly
    - *Microsoft AI Chatter Bot: **Tay***
- As the AI may be poisoned and mischived during the training process via training data, it can also be fooled after the learning process is over. If attacker finds out the way it learned, he may slightly change the things to go through the AI
- An AI that uses real-world information can release confidential information like SSNs etc by being fooled.
- Preventing:
    - Secure the training data
    - Cross check and verify it
    - Constantly retrain with more and better data
    - Train the AI with possible poisoning

### Supply Chain Attacks
- **Supply Chain**: It is the chain of manufacturing of a prodcut from beginning to end. *Includes: raw materials, suplliers, manufacturers, distributors, customers, consumers*
- Attackers can infect any step along the way; *people trust their suppliers...*
- One exploit can infect the entire chain.
- Target Corporation breach, Nov 2013:
    - 40 million credit cards stolen
    - Via a heating and AC firm technicians' VPN systems
- **Supply Chain Cyber Security**:
    - Can you trust your new server/switch/router/firewall/software
- Use a small supplier base
- Tighten control of vendors
- Stricten controls over policies and procedures
- Make sure the security is also a part of the entire plan
- There must be a limit to trust

### Cloud-Based vs On-Premises Attacks
- Two categories for IT security:
    - Cloud-based
    - On-premises
- Cloud-based:
    - Is centralized and costs less
    - No dedicated hardware, no data center to secure
    - A third-party handles everything
- On-premises:
    - Puts the security burden on the client
    - Data center security and infrastructure costs
- On-premises security:
    - Customize your security posture; *full control*
    - On-site IT team can manage security better; *Can ensure everything is secure*
    - However can be expensive and difficult to staff
    - Local team maintains uptime and availability; *system checks any time, no phone call for support*
    - Security changes can take time; *new equipment, configurations, additional costs*
- Cloud-based security:
    - Data is in a secure environment; *No physical access*
    - However third-party may have access to the data
    - Cloud providers are managing large-scale security; *automated signature and security updates*
    - Users must follow security best-pactices
    - Limited downtime; *extensive fault tolerance*
    - 7/24/365 monitoring
    - Scalable security options; *one-click security deployments*
    - However may not be as cutomizable as necessary 

### Cryptographic Attacks
- Can we be sure that an encrypted file from source to destination, is really secure or changed somewhere between?
- Although attacker doesn't know the decrypt key, they may break the safe
- Finding ways to undo security:
    - Many potential cryptographic shortcomings
    - Is often the implementation
1. **Birthday Attack**
    - In a classroom sharing the same birthday scenario
    - In digital world, this is called as *hash collision*
    - **Hash collision** is the same hash value for two different plaintexts; *finding a collision through brute force*
    - The attacker will generate multiple versions of plaintext to match the hashes
    - Hash digests supposed to be unique
    - Different input data should never create the same hash
    - **MD5** *(Message Digest Algorithm 5)*:
        - First published in 1992
        - Collisions identified in 1996<br><img src="https://i.ibb.co/zhWLDWH/MD5-Collision.png">
    - It may be done to create a legitimate seen CA certificates!

2. **Downgrade Attack**
- Instead of using good encryption, make the communicators use something that's not that great by sitting in the middle
- So force the systems to downgrade their security
- 2014 - TLS *(Transport Layer Security)* Vulnerability POODLE *(Padding Oracle On Downgraded Legacy Encrypiton)*:
    - **On-path attack**
    - Force clients to fallback to SSL 3.0
    - SSL 3.0 has significant cryptographic vulnerabilities
    - Because of POODLE, modern browsers won't fallback to SSL 3.0

## 1.3
### Privilege Escalation
- Gain higher-level access to a system,
    - Exploit vulnerability
    - Might be a bug or design flaw
- Simply means more capabilities
- These are high-priority vulnerability patches
- **Horizontal Escalation**: User A can access user B resources
- Mitigating:
    - Patch quickly
    - Update AV/AM
    - **Data Execution Prevention**: Only data in executable areas can run; *Vulnerabilities that try to run an application from the data section of the memory would be blocked*
    - **Address Space Layour Randomization**: Prevent a buffer overrun at a known memory address
- CVE-2020-1530: Windows Remote Access Elevation of Privilege vulnerability:
    - Attacker would execute a program on a victim computer

### Cross-site Scripting (XSS)
- Originally called cross-site because information from one site could be shared with another thanks to some browser security flaws
- One of the most common vulnerability on web based apps
- Malware that uses JavaScript
1. Non-persistent (reflected) XSS Attack
    - Website allows scripts to run in user input, *search box is the most common*
    - Attacker emails a link that takes advantage of this vulnerability; *runs a script that sends credentials/session IDs/cookies to the attacker*
    - Script embedded in URL executes in the victim's browser; *as if it came from the server*
    - Attacker uses credentials/session IDs/cookies to steal victim's information
    - By getting a **session ID** attacker can simply log in without any id or password
2. Persistant (stored) XSS Attack
    - Can be stored permenantly on the server.
    - Anyone visiting that page would be running the script
    - Often a website with posts on it
    - Once the attacker posts the malicious message, everyone who reach to that particular post will also get that malicious script and run it on their local machine
    - No specific target
    - For social networking, this can spread quickly; *as it's shared among people, more people gonna see and so run the script*
    - Example:
        - June 2017, Subaru website
        - Users get an authentication token
        - It never expires *(which is bad)*!
        - A valid token allowed any service request
        - Adding email to your car/account
        - Web front-end included XSS vulnerability
        - A user clicks malicious link, and you have their token
- Protecting:
    - Never click a link especially within your emails
    - Go to the specified website and log in manually
    - Consider disabling JavaScript or use an extension to control
    - Keep your browser and apps updated
    - Validate input; *don't allow users to add their own scripts to an input field*
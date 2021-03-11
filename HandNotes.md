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

### Viruses and Worms
1. Virus
- Malware that can replicate it self
> It needs the user to execute a program to start the replicaton process!
- Can use **the OS** or **the Network** to replicate itself
- May or may not cause problems
- Anti-virus is benefical
- Keep the signatures of anti-virus updated
  
1. 1. **Program Viruses**: They are part of the app
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
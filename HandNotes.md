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
- Mail gateways
    - Stop it at the gateway before it reaches the user
    - On-site or cloud-based
- Identifying spam:
    1. **Allowed list**
    1. **SMTP standatds checking**: *Block anything that doesn't follow RFC standards*
    1. **rDNS - reverse DNS**: *Block email where the sender's domain doesn't match the IP*
    1. **Tarpitting**: *Intentionally slow down the server conversation*
    1. **Recipient filtering**: *Block mails not adressed to a valid recipient email address*
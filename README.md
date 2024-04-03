# HTB Nibbles

## Objective

The purpose of this Lab is to achieve highest privilege escalation possible.
### Skills Learned

- Usage of NMap to perform basic network enumeration.  The target machine associated with this lab provides us with the IP address making this a grey-box PenTest.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of Linux and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- NMap
- GoBuster: used mainly for brute-forcing files
- Metasploit

## Steps
<img width="819" alt="Nibbles1" src="https://github.com/WCrawf02/HTB-Nibbles/assets/149023031/cb2802da-1f30-42dd-bc4a-4e358c3f02cf">

- The use of NMap commmand line, able to see any open ports on target machine
- Quick google search of the open port gave more insight to potential vulnerabilties
<img width="736" alt="Nibbles2" src="https://github.com/WCrawf02/HTB-Nibbles/assets/149023031/1d9f7f72-4b7b-4718-845c-5101536a64be">

- Able to utilize netcat tool to obtain "banner"

<img width="1095" alt="Nibbles3" src="https://github.com/WCrawf02/HTB-Nibbles/assets/149023031/330c64bc-99cf-40d8-b480-e1724333a452">

- Utilize Gobuster command to find additional directories (i.e. potential username/password).

<img width="1162" alt="Nibbles4" src="https://github.com/WCrawf02/HTB-Nibbles/assets/149023031/6d2fbb96-51cb-49d2-b2c0-0a5264520a96">

- After some digging around with the info provided by gobuster, was able to find the username of "admin"
<img width="1190" alt="Nibbles5" src="https://github.com/WCrawf02/HTB-Nibbles/assets/149023031/dae1bbbf-4ec8-4ec9-ac7e-a14e219d06a1">

- Uplaoded my payload into target plugins for "Initial Foothold"





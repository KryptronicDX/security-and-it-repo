# Security Links Repository

This is a repository of links I've saved during my career that are all security focused.  They are either to keep up with current events, tools or even repositories themselves.  Feel free to share or share your links!

--------------------


## Table of Contents

- [Active Directory](#active-directory)
  - GPO App Locker Protection
  - Set Local Admin Passwords Using A Random String
- [Internal Auditing] (#internal-auditing)
  - Lepide Auditor
  - Netwrix Free Tools
- [Honey Pots]
  - Canary Tokens
  - Cryptolocker Canary
  - Honeypot Resources
  - Modern Honey Network
  - Ransomware Protection Using FSRM and PowerShell
- [Groups] (#groups]
  - Military Cyber Professionals Association
- [Repos] (#repos)
  - Digital Forensic Tools
  - GRR Rapid Response
  - HackerTalkyTalk
  - OSINT
  - Privacy Tools
  - PwnWiki.io
  - RITA
- [Reporting] (#reporting)
  - ADRecon
  - Infection Monkey
  - Malware Archaeology
  - Open Source SIEM
  - OpenVAS
  - Third-Wall
  - Zeek
- [Resources] (#resources)
  - Does Your Organization Have a Security.txt File?
  - Implementing Least-Privilege Admin
  - Exercise in a Box
  - MITRE ATT&CK
  - PowerShell ♥ the Blue Team
  - Quad 9
  - Security Config Framework
  - Unified Hosts
- [Services] (#services)
  - National Cybersecurity Assessments and Technical Services
- [Software] (#software)
  - GlassWire
  - Log-MD
  - Security Monitor on RPi
  - SwordPhish
- [Training] (#training)
  - Go Phish
  - Phishing Derby
- [Windows] (#windows)
  - Crack and Detect Weak AD Passwords
  - Domain Hardening
  - Harden Windows Settings
  - Pen Testing Active Directory
  
--------------------

## Active Directory

**[`^        Back to Top        ^`](#)**

- [GPO App Locker Protection] (http://community.spiceworks.com/how_to/show/59664) - A Spiceworks how-to on setting up App Locker using GPO, created by JeffatLSU.
- [Set Local Admin Passwords Using A Random String] (https://www.sans.org/blog/reset-local-administrator-password-using-a-different-random-string-on-each-computer-and-recover-the-passwords-securely) - A post by SANS.org on using PowerShell for securely managing the passwords of local admin accounts on Windows.


## Internal Auditing

**[`^        Back to Top        ^`](#)**

- [Lepide Auditor] (https://www.lepide.com) - A tool I came across but haven't used.  I saved as an option in case it was needed.
- [Netwrix Free Tools] (https://www.netwrix.com/top_7_freeware_tools.html) - I've implemented Netwrix at a previous employer that had all these tools, but these are great stand-alone tools for those needing a free solution.


## Honey Pots

**[`^        Back to Top        ^`](#)**

- [Canary Tokens] (http://canarytokens.org/generate) - A free tool to create various tokens that when triggered, will send a notice to the owner.  I implemented Canary at a previous employer and used these tokens for specific items to track intrusion.
- [Cryptolocker Canary] (https://community.spiceworks.com/how_to/100368-cryptolocker-canary-detect-it-early) - A Spiceworks how-to by JustinCredible on how to setup a canary for ransomware.
- [Honeypot Resources] (https://github.com/paralax/awesome-honeypots) - A repo of various honeypot software and resources.
- [Modern Honey Network] (https://github.com/pwnlandia/mhn) - An open-source honeypot software package.
- [Ransomware Protection Using FSRM and PowerShell] (https://blog.netwrix.com/2016/04/11/ransomware-protection-using-fsrm-and-powershell) - A blog post by Netwrix on how to use FSRM and Powershell to add a layer of protection against ransomware.  Lots of great blog posts by Netwrix!


## Groups

**[`^        Back to Top        ^`](#)**

- [Military Cyber Professionals Association] (https://public.milcyber.org) - For those in the military or are veterans, this is a great group to not only meet up with others from the military, but also those focused on security.


## Repos

**[`^        Back to Top        ^`](#)**

- [Digital Forensic Tools] (https://techtalk.gfi.com/top-20-free-digital-forensic-investigation-tools-for-sysadmins) - A post by GFI showcasing 20 free tools to help with forensics.
- [GRR Rapid Response] (https://github.com/google/grr) - GRR is a python client (agent) that is installed on target systems, and python server infrastructure that can manage and talk to clients.
- [HackerTalkyTalk] (https://github.com/1337list/ephemera-miscellany/blob/master/hackertalkytalk.md) - A listing of recordings from different security conferences.
- [OSINT] (https://github.com/jivoi/awesome-osint) - A curated list of amazingly awesome open source intelligence tools and resources.
- [Privacy Tools] (https://www.privacytools.io) - PrivacyTools.io provides services, tools and privacy guides to counter global mass surveillance. Established way back in 2015 after Edward Snowden's revelations and quickly became the most popular guide for Privacy Tools.
- [Pwnwiki.io] (http://pwnwiki.io/#!index.md) - PwnWiki.io is a collection TTPs (tools, tactics, and procedures) for what to do after access has been gained.
- [RITA] (https://github.com/activecm/rita) - RITA is an open source framework for network traffic analysis.  The framework ingests Zeek Logs in TSV format.


## Reporting

**[`^        Back to Top        ^`](#)**

- [ADRecon] (https://github.com/sense-of-security/ADRecon) - ADRecon is a tool which extracts and combines various artefacts (as highlighted below) out of an AD environment. The information can be presented in a specially formatted Microsoft Excel report that includes summary views with metrics to facilitate analysis and provide a holistic picture of the current state of the target AD environment.
- [Infection Monkey] (https://www.guardicore.com/infectionmonkey) - Infection Monkey is an open-source breach and attack simulation (BAS) platform that helps you validate existing controls and identify how attackers might exploit your current network security gaps. 
- [Malware Archaeology] (https://www.malwarearchaeology.com) - A site with free cheat sheets and log settings that can be used to make sure you're catching everything that is essential.
- [Open Source SIEM] (https://cybersecurity.att.com/products/ossim) - AlienVault® OSSIM™, Open Source Security Information and Event Management (SIEM), provides you with a feature-rich open source SIEM complete with event collection, normalization and correlation.
- [OpenVAS] (https://www.openvas.org) - OpenVAS is a full-featured vulnerability scanner. Its capabilities include unauthenticated and authenticated testing, various high-level and low-level internet and industrial protocols, performance tuning for large-scale scans and a powerful internal programming language to implement any type of vulnerability test.
- [Third-Wall] (https://third-wall.com) - Automation and reports software, I haven't used.
- [Zeek] (https://zeek.org) - Zeek is not an active security device, like a firewall or intrusion prevention system. Rather, Zeek sits on a “sensor,” a hardware, software, virtual, or cloud platform that quietly and unobtrusively observes network traffic. Zeek interprets what it sees and creates compact, high-fidelity transaction logs, file content, and fully customized output, suitable for manual review on disk or in a more analyst-friendly tool like a security and information event management (SIEM) system.


## Resources

**[`^        Back to Top        ^`](#)**

- [Does Your Organization Have a Security.txt File?] (https://krebsonsecurity.com/2021/09/does-your-organization-have-a-security-txt-file) - The idea behind Security.txt is straightforward: The organization places a file called security.txt in a predictable place — such as example.com/security.txt, or example.com/.well-known/security.txt. What’s in the security.txt file varies somewhat, but most include links to information about the entity’s vulnerability disclosure policies and a contact email address.
- [Exercise in a Box) (https://www.ncsc.gov.uk/information/exercise-in-a-box) - An online tool which helps organisations find out how resilient they are to cyber attacks and practise their response in a safe environment.
- [MITRE ATT&CK] (https://attack.mitre.org) - MITRE ATT&CK® is a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations. The ATT&CK knowledge base is used as a foundation for the development of specific threat models and methodologies in the private sector, in government, and in the cybersecurity product and service community.
- [PowerShell ♥ the Blue Team] (https://devblogs.microsoft.com/powershell/powershell-the-blue-team) - When you take an assume-breach mindset, you have to assume that an attacker is already on your system. But then you’re left with questions: What did they do? What systems did they connect to? Was any dynamic code invoked, and what was it? PowerShell version 5 (included in Windows 10, and also available for earlier operating systems through the Windows Management Framework) has made significant strides in making sure that the Blue Team has the information it needs to answer these questions.
- [Quad 9] (https://www.quad9.net) - Quad9 is a free service that replaces your default ISP or enterprise Domain Name Server (DNS) configuration and blocks lookups of malicious host names from an up-to-the-minute list of threats.
- [Security Config Framework] - (https://github.com/microsoft/SecCon-Framework/blob/master/windows-security-configuration-framework.md) - To help you prioritize your endpoint hardening work, Microsoft is introducing a new taxonomy for security configurations for Windows 10. In this initial preview, we are simply listing recommended hardware, policies, controls, and behaviors in order to gather feedback from more customers and security experts in order to refine the framework and prioritize opportunities to automate.
- [Unified Hosts] (https://github.com/StevenBlack/hosts) - This repository consolidates several reputable hosts files, and merges them into a unified hosts file with duplicates removed. A variety of tailored hosts files are provided.


## Services

**[`^        Back to Top        ^`](#)**

- [National Cybersecurity Assessments and Technical Services] (https://www.cisa.gov/cyber-resource-hub) - The Cybersecurity and Infrastructure Security Agency offers a range of cybersecurity assessments that evaluate operational resilience, cybersecurity practices, organizational management of external dependencies, and other key elements of a robust and resilient cyber framework. These professional, no-cost assessments are provided upon request on a voluntary basis and can help any organization with managing risk and strengthening the cybersecurity of our Nation's critical infrastructure.


## Software

**[`^        Back to Top        ^`](#)**


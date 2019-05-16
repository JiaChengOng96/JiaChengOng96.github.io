---
layout: post
title:  "Introduction to Penetration Testing"
---

## Penetration Testing

Commonly also known as pen testing or white hat attack, is an ethical practice of identifying and testing a computer system, web application or network infrastructure for potential vulnerabilities that an attacker can used to exploit the system. The main objective of penetration testing is to identify security vulnerabilities of the system and provide mitigation to secure the system.

Generally during an engagement, penetration tester, who perform the pen testing will have to strictly engage the testing within the scope boundaries and provide information to the relevant organisation only. This is important because pen testing is perform ethically to identify vulnerabilities for the organisation and not be use for exploiting the organisation. 

Pen testing can be broken down into 3 main component which includes: 
***
1. Data Gathering Phase 
2. Exploitation Phase
3. Report Writing Phase
***
Each Phase is similar to how business meeting work such as preparation phase (Before meeting), execution phase (During meeting) and reporting phase (After meeting). I will introduce the basic idea of each component and the flow of the whole pen testing.


#### Data Gathering Phase (reconnaissance)

During this phase, tester would seek more information of the target system such as:

1. Scope of the project: what would be test and what would not be test
2. What is the system and what does it do
3. Which company own the target system
4. What known technology used in the system

#### Exploitation Phase (scanning, gaining access)

After gathering all the data, the next phase would be the exploitation phase. Firstly would scan the system such as what ports of the system is open or any way to inflitrate into the system. This include many ways of doing such as writing up own script, search for exploit script on the web or use some of the configuration setting to gain access. 

After gaining access, we will try to maintain the access such as getting a interactive shell then escalate the access right to root. Depend on the scope of engagement, it can varies and any finding such as getting limited shell or remote code execution show more than enough as a vulnerabilities. 

Most important of this phase it to get all screenshot of anything interesting or result. These screenshot would be important for the last phase which is report writing. All the screenshots taken such as action you perform, result it produce, interesting or useful information and any others would definitely help you with the report writing. The last thing you want when writing report is missing screenshot for proof.  


#### Report Writing Phase (reportation)

After the exploitation Phase, report writing is the only business document that client would want to read.

Each finding or approach can be reported into a different report document. Many template for vulnerabilities report writing can be search online and most of the report template consist of several core component state below

1. XXX (Vulnerabilities name) which lead to XXX (consequences)
2. Severity
    - use industry standard, CVSS score
3. Target system
4. screenshot of proof
    - example, using exploit on a system
    - screenshot of getting root on machine
5. Mitigation for the vulnerabilities
    - link to the OWASP or any other sources depending on vulnerabilities

***


## Next up -> Kali Linux and how to setup

Kali linux is a customised for penetration testing of an ubuntu linux operating system. Kali linux distribution come with many pre-installed open sources tools which will aid in performing penetration tools. 

For those who are interested, do visit this [links](https://www.kali.org/downloads/) to download a copy of kali linux image.

------

**To be Continue...**
# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

## AIM:

To use Google for gathering information and perform enumeration of targets

### STEPS:

#### Step 1:

Install kali linux either in partition or virtual box or in live mode

#### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


#### Step 3:
Open terminal and try execute some kali linux commands

### Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

### Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

#### site:
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain youtube.com




![Screenshot 2025-03-15 131422](https://github.com/user-attachments/assets/5d6b604e-7b2d-43f1-b64f-1c39635e21b7)




#### filetype: 

![Screenshot 2025-03-15 131525](https://github.com/user-attachments/assets/c7693014-d26b-4567-a98c-17a11d95a1b3)

This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

#### intext:
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![Screenshot 2025-03-15 131607](https://github.com/user-attachments/assets/b6c3bda8-11f9-4efa-90bb-f4d70dd6934d)



#### inurl:
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![Screenshot 2025-03-15 131944](https://github.com/user-attachments/assets/e40bd9c0-93df-4e1e-a87f-5d37c7653dd9)


#### intitle:
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![Screenshot 2025-03-15 132134](https://github.com/user-attachments/assets/f3e328c6-621c-4eed-ad2b-61f30d141b7f)




#### link:
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![Screenshot 2025-03-15 132314](https://github.com/user-attachments/assets/8ac31cb3-766f-48d1-a8a6-eaa10f614a12)



### DNS Enumeration


#### DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
#### OUTPUT:
![Screenshot 2025-03-15 143109](https://github.com/user-attachments/assets/53d9d0de-13a1-4987-bb60-5be34883ee24)


#### dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
![Screenshot 2025-03-15 142602](https://github.com/user-attachments/assets/e234428e-0b83-4f5b-aeb2-0d7e586f83d8)



#### smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.



![Screenshot 2025-03-15 142324](https://github.com/user-attachments/assets/a0b8e274-b23e-450b-9a36-e35e35166ae5)



#### Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
#### Output
  
![Screenshot 2025-03-15 143643](https://github.com/user-attachments/assets/294fb1d8-e4f7-4025-a841-187a1dffe3f3)
  

#### nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


#### OUTPUT:
 
![Screenshot 2025-03-15 142201](https://github.com/user-attachments/assets/a6c17938-31d0-4574-8ec4-dcc59cc7c699)


### RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully


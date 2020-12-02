# CATzombies

<h4 align="center">
   <img src="/IMG/header.png" width=400>
</h4>

CATzombies green is a Python 3 app for SECURITY TESTING PURPOSES ONLY! 

CATzombies is an HTTP DoS Test Tool. 

Attack Vector exploited: HTTP Keep Alive + NoCache


## How To Use 


   USAGE: ./CATzombies.py <url> [OPTIONS]

   OPTIONS:
           Flag                 Description                                    Default 
       -u, --useragents   File with user-agents to use                     (default: randomly generated) 
       -w, --workers      Number of concurrent workers                     (default: 50) 
       -s, --sockets      Number of concurrent sockets                     (default: 30)
       -m, --method       HTTP Method to use 'get' or 'post'  or 'random'  (default: get)  
       -d, --debug        Enable Debug Mode [more verbose output]          (default: False)  
       -n, --nosslcheck   Do not verify SSL Certificate                    (default: True) 
       -h, --help         Shows this help


## Utilities

* util/getuas.py - Fetches user-agent lists from http://www.useragentstring.com/pages/useragentstring.php subpages (ex: ./getuas.py "http://www.useragentstring.com/pages/useragentstring.php?name=All") *REQUIRES BEAUTIFULSOUP4*
* res/lists/useragents - Text lists (one per line) of User-Agent strings (from http://www.useragentstring.com)


## Updates 

* support for not verifying SSL Certificates.  
* randomly created user agents (still RFC compliant).
* Removed silly referers and user agents. Improved randomness of referers. Added external user-agent list support.
* Changed from threading to multiprocessing. Still has some bugs to resolve like I still don't know how to propperly shutdown the manager.


## LEGAL NOTICE

THIS SOFTWARE IS PROVIDED FOR EDUCATIONAL USE ONLY! IF YOU ENGAGE IN ANY ILLEGAL ACTIVITY THE AUTHOR DOES NOT TAKE ANY RESPONSIBILITY FOR IT. BY USING THIS SOFTWARE YOU AGREE WITH THESE TERMS.


## ScreenShot for this Tools

<h4 align="center">
   <img src="/IMG/mid.png" width=400>
</h4>


## FOR SUPPORT

OU CAN DONATION ON MY DOGE ADDRESS 

Donation : **DRo6EgsZoyWWjWSbEUbYKCxFvBJjHHbxf5** [DOGE]


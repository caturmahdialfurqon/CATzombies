# CATzombies

<h4 align="center">
<img src="/img/header.png" width=400>
</h4>

CATzombies is a Python 3 app for SECURITY TESTING PURPOSES ONLY!

CATzombies is an HTTP DoS Test Tool.

Attack Vector exploited: HTTP Keep Alive + NoCache


## How To Use 

     USAGE: ./CATzombies.py <url> [OPTIONS]

     OPTIONS:
        Flag           Description                     Default
        -u, --useragents   File with user-agents to use                     (default: randomly generated)
        -w, --workers      Number of concurrent workers                     (default: 50)
        -s, --sockets      Number of concurrent sockets                     (default: 30)
        -m, --method       HTTP Method to use 'get' or 'post'  or 'random'  (default: get)
        -d, --debug        Enable Debug Mode [more verbose output]          (default: False)
        -n, --nosslcheck   Do not verify SSL Certificate                    (default: True)


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
<img src="/img/mid.png" width=600>
</h4>


<br>
## 🤜🏻🤛🏻 Support Me

You can support me and [buy me a coffee][8], if you want. 🙏🏻

[![ME Furqonic](https://img.shields.io/badge/SUPPORT-ME-succsess.svg?style=flat)](Support)
<br>
[![Paypal Furqonic](https://img.shields.io/badge/$-Paypal-informasional.svg?style=flat)](https://paypal.me/caturmahdialfurqon)
<br>
[![BSC Furqonic](https://img.shields.io/badge/BSC-0x0cacb28b61d9e4240aad91da5b7ba039a3b563aa-informational.svg?style=flat)](0x0cacb28b61d9e4240aad91da5b7ba039a3b563aa)
<br>
[![BTC Furqonic](https://img.shields.io/badge/BTC-1FKswVkZzu4qgnJGGBnd63mhVfRKVHgSt1-informational.svg?style=flat)](1FKswVkZzu4qgnJGGBnd63mhVfRKVHgSt1)
<br>
[![DOGE Furqonic](https://img.shields.io/badge/DOGE-DAb3FBAQckm9DtkM6QxaXoQ61WN8kSHVbk-informational.svg?style=flat)](DAb3FBAQckm9DtkM6QxaXoQ61WN8kSHVbk)
<br>
[![LTC Furqonic](https://img.shields.io/badge/LTC-M8FkA5XMxsj6NP5MNrfkhqFWYUPbcunQgh-informational.svg?style=flat)](M8FkA5XMxsj6NP5MNrfkhqFWYUPbcunQgh)

<br>


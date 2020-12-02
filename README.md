
```diff
# CATzombies green
```
<h4 align="center">
   <img src="/IMG/header.png" width=400>
</h4>
```diff
@@ CATzombies green is a Python 3 app for SECURITY TESTING PURPOSES ONLY! red @@

@@ CATzombies is an HTTP DoS Test Tool. grey @@

@@ Attack Vector exploited: HTTP Keep Alive + NoCache grey @@
```
```diff
## How To Use orange
```
```diff
   - USAGE: ./CATzombies.py <url> [OPTIONS] red

   + OPTIONS:
            @@ Flag                 Description                                    Default grey @@
@@        -u, --useragents   File with user-agents to use                     (default: randomly generated) green @@
@@        -w, --workers      Number of concurrent workers                     (default: 50) green @@
@@        -s, --sockets      Number of concurrent sockets                     (default: 30) green @@
@@        -m, --method       HTTP Method to use 'get' or 'post'  or 'random'  (default: get) green @@
@@        -d, --debug        Enable Debug Mode [more verbose output]          (default: False) green @@
@@        -n, --nosslcheck   Do not verify SSL Certificate                    (default: True) green @@
@@        -h, --help         Shows this help
```
```diff
## Utilities orange
```
* util/getuas.py - Fetches user-agent lists from http://www.useragentstring.com/pages/useragentstring.php subpages (ex: ./getuas.py "http://www.useragentstring.com/pages/useragentstring.php?name=All") *REQUIRES BEAUTIFULSOUP4*
* res/lists/useragents - Text lists (one per line) of User-Agent strings (from http://www.useragentstring.com)

```diff
## Updates orange

@@ support for not verifying SSL Certificates green @@
@@ randomly created user agents (still RFC compliant). green @@
@@ Removed silly referers and user agents. Improved randomness of referers. Added external user-agent list support. green @@
@@ Changed from threading to multiprocessing. Still has some bugs to resolve like I still don't know how to propperly shutdown the manager. green @@
```
``` diff
## LEGAL NOTICE orange

@@ THIS SOFTWARE IS PROVIDED FOR EDUCATIONAL USE ONLY! IF YOU ENGAGE IN ANY ILLEGAL ACTIVITY THE AUTHOR DOES NOT TAKE ANY RESPONSIBILITY FOR IT. BY USING THIS SOFTWARE YOU AGREE WITH THESE TERMS. red @@
```
```diff
## ScreenShot for this Tools orange
```
<h4 align="center">
   <img src="/IMG/mid.png" width=400>
</h4>

``` diff
## FOR SUPPORT orange

@@Y OU CAN DONATION ON MY DOGE ADDRESS grey @@

@@ Donation : **DRo6EgsZoyWWjWSbEUbYKCxFvBJjHHbxf5** [DOGE] blue @@
```

# Week-9
Time spent: >24 hours spent in total

Objective: Learn about Network Security(NetSec) by attacking and being attacked vulnarable networked resources. For this purpose a basic honeypot will be stood up and its effectiveness at detecting and/or collecting data about an attack will be demonstrated.

The Honeypot Built:
A honeypot is a decoy application, server, or other networked resource that intentionally exposes insecure features which, when exploited by an attacker, will reveal information about the methods, tools, and possibly even the identity of that attacker. For this assignment, Honeypot Dionaea over HTTP is deployed as mhn-honeypot-1.

Ubunti-Snort was also used in Honeypot-2.

An overview of the steps taken includes;

Sign up for a Google cloud account
Install gcloud in the host machine so that gcloud command can be run from the host machine
Set up firewall rule for MHN Admin
Create MHN Admin VM and install MHN Admin Application. MHN supports multiple honeypots, each of which has a slightly different purpose.
Create MHN Honeypot VM and install the honeypot application; deploy Dionaea over HTTP, a honeypot used to trap malware samples then wait to be attacked

Issues Encountered:
The installtion was tedious and required a lot of background knowledge of google aplications and networking. At first, I couldn't admin-console, not realizing that http was needed. 

The next issue was getting the seesion.json file. Following the commands given in instructions, the commands would not work on Windows, Google Cloud Platform SDK. I found a work around involving logging into google cloud account and using browser ssh terminal, which allowed a direct download over the browser. 

At time of this wrtieup, there were close to 4000 attacks from dionaea and 500 from snort.

https://github.com/hareshseepersad/Week-9/blob/master/session.json

[]https://github.com/hareshseepersad/Week-9/blob/master/Week%209-Honeypot.gif

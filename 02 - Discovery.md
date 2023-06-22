Mapping Tips:
- Google
- Smart* Directory Brute Forcing
  - RAFT lists (included in Seclists)
  - SVN Digger (included in Seclists)
  -  Git Digger
- Platform Identification:
  - Wapplyzer (Chrome)
  - Builtwith (Chrome)
  - retire.js (cmd-line or Burp)
  - Check CVE’s
- Auxiliary
  - WPScan
  -CMSmap

`amass intel --asn XXX` - Get ASN from https://bgp.he.net/

`amass enum -d 'DOMAIN.COM'


### Whois reverse
https://www.whoxy.com/

### BuiltWith 
https://builtwith.com/
Set of anayltic trackers and it will show relationships 



Burp suite 
- Set Scope - advanced scope control 
	- Add domain name  
	-Crawl from site map - show in scope items
	- Scan 
		- Crawl (no audit)
		- scan config - library 
			- crwal strategy -  faster
			- Never stop crawl to app error
			- Can resource pool - maybe 20-30


cat subdomains.txt | httpx ––silent >> alive.txt && cat alive.txt | katana ––silent >> endpoints.txt && cat endpoints.txt | nuclei -t <YOUR_TEMPLATES>


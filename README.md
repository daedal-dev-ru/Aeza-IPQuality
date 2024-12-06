<p align="center">
<img src="https://hits.seeyoufarm.com/api/count/keep/badge.svg?url=https%3A%2F%2Fip.check.place&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Runs&edge_flat=false"/> 
<img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fxykt%2FIPQuality&count_bg=%233DC8C0&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Visits&edge_flat=false"/> 
<a href="/LICENSE"><img src="https://img.shields.io/badge/License-AGPL%20v3-blue.svg" alt="license" /></a>  
</p>

## IP Quality Check Script

**Supported OS/Platform: Ubuntu | Debian | Linux Mint | Fedora | Red Hat Enterprise Linux (RHEL) | CentOS | Arch Linux | Manjaro | Alpine Linux | AlmaLinux | Rocky Linux | macOS | Anolis OS | Alibaba Cloud Linux | SUSE Linux | openSUSE | Void Linux**

- Bilingual support in English and Russian
- Supports dual-stack queries for IPv4/IPv6
- Beautifully formatted, intuitive display, optimized for single-screen multi-terminal display, facilitating screenshot sharing
- Six modules: Basic Information, IP Type, Risk Score, Risk Factors, Streaming Media Unlocking, and Post Office Check
- Basic data sourced from the *Maxmind* database
- Risk information integrated from multiple databases: *IPinfo / ipregistry / ipapi / AbuseIPDB / IP2LOCATION / IPQS / DB-IP / SCAMALYTICS / IPWHOIS / Cloudflare*
- Streaming and AI service providers' unlocking and type detection: *TikTok / Netflix / Youtube / Amazon / Spotify / ChatGPT*
- Connectivity tests for multiple email providers: *Gmail / Outlook / Yahoo / Apple / QQ / Mail.ru / AOL / Mail.ru / *
- Over 400 IP address blacklist database checks

##### Screenshots
![Screenshot](https://raw.githubusercontent.com/xykt/IPQuality/main/img/en_IPv4.svg)

## How to Use

##### English version of dual-stack test:
````bash
bash <(curl -Ls IP.Check.Place) -l en
````

##### Russian version of dual-stack test:
````bash
bash <(curl -Ls IP.Check.Place) -l ru
````

##### IPv4 only test:
````bash
bash <(curl -Ls IP.Check.Place) -l en -4
````

##### IPv6 only test:
````bash
bash <(curl -Ls IP.Check.Place) -l en -6
````

##### Specify network interface:
````bash
bash <(curl -Ls IP.Check.Place) -l en -i eth0
````

##### Show full IP on report:
````bash
bash <(curl -Ls IP.Check.Place) -l en -f
````

##### Basic information multi-language support:
````bash
bash <(curl -Ls IP.Check.Place) -l en|ru
````

# Offensive-OSINT-Tools

This repository consists of tools/links that a expert can use during Pentest/RedTeam. If the tool performs multiple functions, for example collecting subdomains **and** URLs, it will be listed in two places.

## 📖 Table of Contents

- [Search Engines](#-search-engines)
- [Emails collector](#-emails-collector)
- [References in the code](#-references-in-the-code)
- [SubDomain collector](#-subdomain-collector)
- [URL collerctor](#-url-collerctor)
- [Tor](#-tor)
- [Intelligence](#-intelligence)
- [Network Info](#-network-info)
- [DnsHistory](#-dnshistory)
- [FTP servers](#-ftp-servers)
- [Passive Infrastructure scanner](#-passive-infrastructure-scanner)
- [Microsoft Excange](#-microsoft-excange)
- [Telegram](#-telegram)
- [Google Dorks](#-google-dorks)
- [Nickname search](#-nickname-search)
- [Cloud](#-cloud)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## [↑](#-Table-of-Contents) Search Engines

Search Engines for Investigation Domains/IP Addresses.

* [Censys](https://censys.io/)
* [Shodan](https://www.shodan.io/)
* [Greynoise.io](https://viz.greynoise.io/)
* [ZoomEye](https://www.zoomeye.org/)
* [Onyphe](https://www.onyphe.io/)
* [Fofa](https://fofa.info/)
* [Binaryedge](https://app.binaryedge.io/)
* [FullHunt](https://fullhunt.io/)
* [Netlas](https://app.netlas.io/)
* [Quake360](https://quake.360.net/quake/#/index)
* [Criminalip](https://www.criminalip.io/)
* [Synapsint](https://synapsint.com/)
* [Natlas](https://natlas.io/)
* [Leakix](https://leakix.net/)


## [↑](#-Table-of-Contents) Emails collector

Tools that help you collect email addresses. Usually the search requires the domain of the company.

* [Hunter.io](https://hunter.io/)
* [Snov.io](https://snov.io/)
* [Phonebook](https://phonebook.cz/)
* [Poastal](https://github.com/jakecreps/poastal) - Tool that provides valuable information on any email address
* [Email-format](https://www.email-format.com/) - Analyses the company's mail format.
* [h8mail](https://github.com/khast3x/h8mail) - Email OSINT & Password breach hunting tool
* [EmailFinder](https://github.com/Josue87/EmailFinder) - Search emails from a domain through search engines
* [theHarvester](https://github.com/laramies/theHarvester)
* [Anymailfinder](https://anymailfinder.com/) - Find Verified Emails
* [Omail](https://omail.io/leads/download.html)
* [Skymem](https://www.skymem.info/)
* [Signalhire](https://www.signalhire.com/)
* [Rocketreach](https://rocketreach.co/)
* [Infoga](https://github.com/m4ll0k/Infoga)

## [↑](#-Table-of-Contents) References in the code

Tools for finding mentions in code. Useful to search for company/company mentions to find passwords/secrets/confidential information.

* [Searchcode](https://searchcode.com/)
* [Publicwww](https://publicwww.com/)
* [Grep.app](https://grep.app/)

## [↑](#-Table-of-Contents) SubDomain collector

Tools for automatic search of subdomains. Most of them require API keys to work correctly.

### Tools
* [Bbot](https://github.com/blacklanternsecurity/bbot)
* [Sudomy](https://github.com/screetsec/Sudomy)
* [Amass](https://github.com/OWASP/Amass)
* [theHarvester](https://github.com/laramies/theHarvester)
* [Spiderfoot](https://github.com/smicallef/spiderfoot)
* [SubGPT](https://github.com/s0md3v/SubGPT) - SubGPT looks at subdomains you have already discovered for a domain and uses BingGPT to find more.
* [alterx](https://github.com/projectdiscovery/alterx) - Fast and customizable subdomain wordlist generator using DSL.

*Only sites/tools whose search is not automated by the tools above are listed here.*
* [TI.defender.microsoft](https://ti.defender.microsoft.com/)
* [Securitytrails](https://securitytrails.com/)
* [Shrewdeye](https://shrewdeye.app/)
* [Phonebook](https://phonebook.cz/)
* [Nmmapper](https://nmmapper.com/)

## [↑](#-Table-of-Contents) URL collerctor

Tools for passive collection of URLs for their subsequent analysis.

* [Gau](https://github.com/lc/gau)
* [Waymore](https://github.com/xnl-h4ck3r/waymore)
* [Spiderfoot](https://github.com/smicallef/spiderfoot)
* [theHarvester](https://github.com/laramies/theHarvester)

## [↑](#-Table-of-Contents) Tor

An undiscovered area, the author is too dumb for that. Will gradually expand.

* [Ahmia](https://ahmia.fi/)

## [↑](#-Table-of-Contents) Intelligence

Threat Intelligence tools containing extensive company information, subdomains, DNS information, URLs and much more.  

* [TI.defender.microsoft](https://ti.defender.microsoft.com/)
* [Securitytrails](https://securitytrails.com/)
* [Pulsedive](https://pulsedive.com/)
* [ThreatBook](https://threatbook.io/)
* [Alienvault](https://otx.alienvault.com/)


## [↑](#-Table-of-Contents) Network Info

IP/Domain network analysis tools.

* [Bgp.he](https://bgp.he.net/)
* [Asnlookup](https://asnlookup.com/)
* [Bgp.tools](https://bgp.tools/)
* [Myip](https://myip.ms/)
* [IpInfo](https://ipinfo.io/) | [Cmd version](https://github.com/ipinfo/cli)
* [Whoisxmlapi](https://main.whoisxmlapi.com/)

## [↑](#-Table-of-Contents) DnsHistory

Tools for viewing the DNS history of a domain.

* [Dnshistory](https://dnshistory.org/)
* [Viewdns](https://viewdns.info/)
* [TI.defender.microsoft](https://ti.defender.microsoft.com/)
* [Securitytrails](https://securitytrails.com/)


## [↑](#-Table-of-Contents) FTP servers

Tools allowing you to search for and download files located on public FTP servers. 

* [Searchftps](https://www.searchftps.net/)

## [↑](#-Table-of-Contents) Passive Infrastructure scanner

Tools for automated passive IP address/subnet scanning.

* [Smap](https://github.com/s0md3v/Smap)
* [Nmap-censys](https://github.com/censys/nmap-censys)


## [↑](#-Table-of-Contents) Microsoft Excange 

Tools to help with passive/semi-passive analysis of Microsoft Excgange.

* [ExchangeFinder](https://github.com/mhaskar/ExchangeFinder) | #SemiOSINT

## [↑](#-Table-of-Contents) Telegram

Tools for investigating Telegram chats.

* [Telepathy](https://github.com/jordanwildon/Telepathy)

## [↑](#-Table-of-Contents) Google Dorks

Tools for Google Dorks.

* [Pagodo](https://github.com/opsdisk/pagodo)
* [Google hacking database](https://www.exploit-db.com/google-hacking-database)
* [](https://recruitin.net/) - Compiles Google dorks to search on LinkedIn, Dribbble, GitHub, Xing, StackOverflow, Twitter
* [Search](https://github.com/pbkompasz/search) - Custom queries in Google

## [↑](#-Table-of-Contents) Nickname search

Nickname search tools.

* [maigret](https://github.com/soxoj/maigret)
* [Sherlock](https://github.com/sherlock-project/sherlock)
* [Social analyzer](https://github.com/qeeqbox/social-analyzer)
* [nexfil](https://github.com/thewhiteh4t/nexfil)
* [whatsmyname](https://github.com/webbreacher/whatsmyname)
* [snoop](https://github.com/snooppr/snoop)
* [userrecon](https://github.com/wishihab/userrecon)
* [NicknameFinder](https://github.com/restanse/NicknameFinder)
* [gideon](https://github.com/YouVBeenHacked/gideon)
* [Arina-OSINT](https://github.com/AlexC-ux/Arina-OSINT)
* [netizenship](https://github.com/rahulrajpl/netizenship)
* [Search4](https://github.com/0xknown/Search4)
* [socialscan](https://github.com/iojw/socialscan)
* [Sherlock](https://github.com/mesuutt/sherlock)
* [recon-ng](https://github.com/lanmaster53/recon-ng/)
* [SocialPath](https://github.com/woj-ciech/SocialPath)

## [↑](#-Table-of-Contents) Cloud

[Cloud_sherlock](https://github.com/Group-IB/cloud_sherlock)

## Warning

Some of the sites included might require registration or offer more data for $$$, but you should be able to get at least a portion of the available information for no cost.

----------------------------------------------------------
*Inspired by https://github.com/jivoi/awesome-osint*

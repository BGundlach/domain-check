#domain-check#
 ============

A bash script to check which tld's a particular domain is available under.

##Installation##
Unzip this file in your $PATH make sure it's executeable and dmntools is writeable

###Dependencies###
**Python is required to update server list**

*dirname may not work on some emulators breaking the script*

##Usage##
```
USAGE:
  dmnchk [options] domains(without tld extentions)
 
EXAMPLE: 
  dmnchk purple
Sample Output: 
  purple.com : available
  purple.net : available
  purple.ac : available
 etc.
 
OPTIONS:
  -c classic domains only .com .net .org .biz
  -a search all (include nonenglish tlds)
  -h display this help message
  -l list all tlds in list (can be combined with -a)
  -u update domain list
```

##Whois server scraping##
Added the python script github.com/voronkovich/whoislist to allow updating server list

##To Do##

Separate Generic and Country Code TLDs
# domain-check
version 1.1

A bash script to check which tld's a particular domain is available under.

## Installation

```bash
# Go to where you want to put the files
cd /opt #(or ~/bin or wherever you want to drop these files)

# copy the filez
git clone https://github.com/BGundlach/domain-check.git

# link files to your PATH
ln -sT domain-check/dmnchk ~/bin/dmnchk # assuming ~/bin is in your $PATH
```

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

##To Do##
Separate Generic and Country Code TLDs
accept domains with tlds

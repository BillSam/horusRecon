```
  _     ____  ____ ___  _ ____  _____ ____ ____  _
 / \   /  _ \/_   \\  \///  __\/  __//   _Y  _ \/ \  /|
 | |   | / \| /   / \  / |  \/||  \  |  / | / \|| |\ ||
 | |_/\| |-||/   /_ / /  |    /|  /_ |  \_| \_/|| | \||
 \____/\_/ \|\____//_/   \_/\_\\____\\____|____/\_/  \|

```

# Usage

`./horusRecon.sh -d domain.com`



# About

LazyRecon is a script written in Bash, it is intended to automate some tedious tasks of reconnaissance and information gathering.
This tool allows you to gather some information that should help you identify what to do next and where to look.


# Main Features 
- Create a dated folder with recon notes
- Grab subdomains using:

      * Sublist3r, certspotter and cert.sh
      * Dns bruteforcing using massdns
      
- Find any CNAME records pointing to unused cloud services like aws
- Probe for live hosts over ports 80/443
- Grab a screenshots of responsive hosts 
- Scrape wayback for data:

      * Extract javascript files
      * Build custom parameter wordlist, ready to be loaded later into Burp intruder or any other tool
      * Extract any urls with .jsp, .php or .aspx and store them for further inspection
      
- Perform nmap on specific ports 
- Get dns information about every subdomain
- Perform dirsearch for all subdomains 
- Generate a HTML report with output from the tools above
- Improved reporting and less output while doing the work
- Dark mode for html reports


# DEMO
![cli output](https://github.com/plenumlab/lazyrecon/raw/dev/upgrade/recon.gif)
=================================================================================
![report demo](https://github.com/plenumlab/lazyrecon/raw/dev/upgrade/report.gif)

# Authors and Thanks
This script makes use of tools developped by the following people
- [Tom Hudson - Tomonomnom](https://github.com/tomnomnom)
- [Ahmed Aboul-Ela - Aboul3la](https://github.com/aboul3la)
- [B. Blechschmidt - Blechschmidt](https://github.com/blechschmidt)
- [Thomas D. - Maaaaz](https://github.com/maaaaz)
- [Daniel Miessler - Danielmiessler](https://github.com/danielmiessler)


# TO DO
- Report only mode to generate reports for old dirsearch data






**Warning:** This code was originally created for personal use, it generates a substantial amount of traffic, please use with caution. 



1. Hash Calculator File: https://download.yubsoft.com/x64/hash.exe

Putty:
1. Putty-src.zip: https://the.earth.li/~sgtatham/putty/latest/putty-src.zip
2. Checksums: https://the.earth.li/~sgtatham/putty/0.83/md5sums

FTP:
1. Server:     ftpupload.net 
2. User:       if0_40939029
3. Pass:       zvSigCPkBZklJpK

New FTP:

1. Host: 15.207.114.186
2. User: ftpuser
3. Pass: password

Kali Linux VM for Virtual BOX: https://cdimage.kali.org/kali-2025.4/kali-linux-2025.4-virtualbox-amd64.7z

Nmap Cheatsheet: https://stationx-public-download.s3.us-west-2.amazonaws.com/nmap_cheet_sheet_v7.pdf

Commands:

Nmap Scans:

1. nmap 10.211.55.10 (Only Top 1000 Ports)
2. nmap google.com -v  (Domain Scan and Versbose Op)
3. nmap 10.211.55.10 -p 22,21,80 -v
4. nmap 10.211.55.10 -p 20-40 -v
5. nmap 10.211.55.10 -p- -v
6. nmap 10.211.55.10 -p 80 -v -sV
7. nmap 10.211.55.10 -O -v 
8. nmap 10.211.55.10 -T5 
9. nmap 10.211.55.10-255 
10. nmap -iL ips.txt -p 80 -v
11. nmap -iL ips.txt -oN (Normal)
nmap -iL ips.txt -oG (Grep)
nmap -iL ips.txt -oX (XML)
nmap -iL ips.txt -oA (All formats)

1. nc -z 192.168.82.43 1-100
2. nc -lvp 4444 > file.txt
3. cat file.txt
4. nc -lvp 4444 > file.txt

Download File using wget:
1. wget "https://raw.githubusercontent.com/WillieStevenson/top-100-passwords/refs/heads/master/password-list.txt"

SecLists Passwords Wordlist:
1. https://github.com/danielmiessler/SecLists/tree/master/Passwords/Common-Credentials
2. Indian Wordlists : https://github.com/zxcv32/indian-wordlist/blob/main/indian-passwords#L23

Kali Purple VDI to run with Virtual Box:
https://drive.google.com/file/d/1kzgkxQ67IKa4tOx85jh9KSXf8SwjFYny/view?usp=sharing

Password Checker : https://www.passwordmonster.com/

Validate Email: https://verifalia.com/validate-email

ShellPhish: https://github.com/AbirHasan2005/ShellPhish

Ransomware: https://github.com/guilhermej/py_ransomware/tree/master

Steago: https://futureboy.us/stegano/


Email Header Analysis: https://mha.azurewebsites.net/

Alexa Top 1 M Websites: https://github.com/mozilla/cipherscan/tree/master/top1m

Shell Script to check Email Spoofing: 
1. cat targets.txt| while read host do; do dig +short TXT $host | grep "\-all" && print $host "Not VULN"  || print $host "VULN";done

2. cat targets.txt| while read host do; do dig +short TXT $host | grep "\-all" && echo -e '\e[0;31m' $host "Not VULN"  || echo -e '\e[0;32m' $host "VULN";done

Chrome Extension:
1. Chrome: Link Grabber: https://chromewebstore.google.com/detail/link-grabber/caodelkhipncidmoebgbbeemedohcdma?hl=en-GB&utm_source=ext_sidebar
2. FireFox: addons.mozilla.org/en-US/firefox/addon/link-gopher/

Best DNS Wordlist: https://wordlists.assetnote.io/

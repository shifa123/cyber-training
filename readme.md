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

nc -z 192.168.82.43 1-100
nc -lvp 4444 > file.txt
cat file.txt
465  nc -lvp 4444 > file.txt

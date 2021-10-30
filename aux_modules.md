# Auxiliary Modules for Metasploit framework
**metasploit platform for using security tools and exploits**
### Port Scanner
msf > use auxiliary/scanner/portscan/tcp
msf > set RHOSTS 10.10.10.0/24
msf > run

### DNS Enumeration
msf > use auxiliary/gather/dns_enum
msf > set DOMAIN target.tgt
msf > run

### FTP Server
msf > use auxiliary/server/ftp
msf > set FTPROOT /tmp/ftproot
msf > run

# Enumeration

## SMB (139, 445)

**NSE**

Vulnerabilities

`nmap --script smb-vuln-* -p <PORTS> <IP>`

`nmap --script smb-check-vulns.nse -p <PORTS> <IP>`

OS Discovery

`nmap --script smb-os-discovery <IP>`

**Other Tools**

`nmblookup -A <IP>`

`smbclient -L //<IP>`

`smbclient //MOUNT/share -I <IP> -N`

`rpcclient -U "" <IP>`

`enum4linux -a <IP>`




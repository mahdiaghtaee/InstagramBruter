# Instagram Bruter
This program will brute force any Instagram account you send it its way given a list of proxies.

# Proxies 
The system needs a list of proxies to work. Once uploaded, proxies are saved into a database.

# Upload
Upload a list of proxies into the program. The proxy file must have a format of ip:port
proxies_list.txt
```
python.exe .../instagram.py -px .../proxies_list.txt
```
```
172.67.190.88:80
172.64.18.156:80
98.162.25.7:31653
98.178.72.21:10919
```

# Stats
This gives an insight into the health of the proxies in the database.
```
.../python.exe .../instagram.py --stats
```

# Usage
python instagram.py -u <username> -p <passlist>

# Run
[-] Wordlist: passlist.txt
[-] Username: sss.1
[-] Password: 272
[-] Complete: 45.51%
[-] Attempts: 228
[-] Browsers: 273
[-] Exists: True

# Stop
[-] Wordlist: passlist.txt
[-] Username: sss.1
[-] Password: sss.123
[-] Complete: 62.67%
[-] Attempts: 314
[-] Browsers: 185
[-] Exists: True

[!] Password Found
[+] Username: sss.1
[+] Password: sss.123


# Demo



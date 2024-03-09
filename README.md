# ipsweep.sh

# Installation:
```bash

# Clone ipsweep repository & enter the folder
git clone https://github.com/brambeekman/ipsweep
cd ipsweep

# Execute the script
./ipsweep.sh [ip address without last number]
```
# Extra use cases
```bash
# Save output to a file
./ipsweep.sh 192.168.56 > ips.txt

# Use save file with nmap to scan IPs
for ip in $(cat ips.txt); do nmap $ip; done
```

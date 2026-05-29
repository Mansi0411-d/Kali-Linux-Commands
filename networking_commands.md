# 🌐 Networking Commands

- `ifconfig` → Show IP and interfaces  
- `ping 8.8.8.8` → Test connectivity  
- `netstat -tuln` → Show active ports  
- `curl example.com` → Fetch a webpage

  # Interface & IP
ifconfig              # Show IP addresses and interfaces
ip addr show          # Modern alternative to ifconfig
ip route              # Display routing table
iwconfig              # Show wireless interface details

 # Connectivity
ping google.com       # Test connectivity
traceroute google.com # Show path packets take
curl example.com      # Fetch webpage data
wget http://site.com  # Download files from web

# Active Connections
netstat -tulnp        # Show active ports and processes
ss -tulnp             # Modern alternative to netstat
lsof -i               # List open files and network connections

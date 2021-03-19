# VoIP-FreePBX-Setup-and-Maintenance
Scripts, keys, and other items for Setting up FreePBX Servers hosted on FreePBXHosting.com

# Key Copy Script
Appends our engineering team's ssh keys to ~/.ssh/authorized_keys.  If ~/.ssh/authorized_keys does not exist it will create it and set the appropriate permissions.
# To use, run on the target server:
curl https://raw.githubusercontent.com/Cyberlynk/VoIP-FreePBX-Setup-and-Maintenance/main/Key%20Copy%20Script | bash

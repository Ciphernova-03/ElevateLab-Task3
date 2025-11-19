I worked with both Windows Firewall and Linux UFW to block and test port 23 (Telnet).

On Windows:
- Opened Windows Defender Firewall (Advanced Settings)
- Created an inbound rule to block port 23
- Tested with: telnet 127.0.0.1 23 → connection failed
- Deleted the firewall rule after testing

On Linux:
- Enabled UFW firewall
- Added a deny rule for port 23
- Tested using telnet → connection refused
- Removed the rule to restore the firewall

Overall, I learned how to add, test, and remove firewall rules on both Windows and Linux.

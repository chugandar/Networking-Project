# Networking-Project-
Using SIP Protocol

# Features
1. Audio Calling
2. Video Calling
3. Audio Conferencing

# Tools and Tech
1. Asterisk 8 server 
2. PortSIP UC (for Android)
3. Zoiper (for Android)
4. TP-LINK 2.4GHz High Power Outdoor CPE Model No. TL-WA5210G
5. A regular laptop to host the Asterisk server

# Instructions
1. Go to the directory where asterisk is installed (/etc/asterisk) 
2. Create backup files for sip.conf, extensions.conf and confbridge.conf in the same directory for safety
3. Create sip.conf by typing sudo vi sip.conf and enter the above code
4. Similarly do it for the other two files
5. Now restart asterisk
6. Connect the phoneto the same wifi
7. 9001, 9002 and 9003 are three different users login to PortSIP using any one of them
8. Use 777 for audio conferencing as admin and 666 as user

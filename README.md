# Description

peer to peer file transfer over LAN using QR codes

# TODO

current implementation uses SDP, but this is a bit of a pain to copy in the information. 

perhaps a STUN connection would be better (and easier) to utilize. 
if that doesn't work, a TURN relay would be the next best thing, but security may be a concern

# NOTES
bridge / proxy to WSL system:
netsh interface portproxy add v4tov4 listenaddress=192.168.50.16 listenport=80 connectaddress=172.21.213.123 connectport=8080

windows firewall must be turned off

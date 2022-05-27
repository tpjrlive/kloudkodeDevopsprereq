# Networking Basics
 
 * route - looks at current routing commands
 * ip route add 192.168.2.0/24 via 192.168.1.1 - Add entries to routing table
 * ip route add default via 192.168.2.1 - Adds default gateway for any traffic outside of network
 * ip link - List and modify interfaces on host
 * ip addr - see ip addresses assiggned.
 * ip address add - set ip addresses on interfaces. 
 * if you want to persist changes you must set them in the etc/network/interfaces file
 * cat /proc/sys/net/ipv4/ip_forward - ip forwarding is activated or not.
 * 

# Networking Basics
## Part 1 - concepts
### IP Address 
IP address  is computer network address.
Two type of address
1.PRIVATE IP
Private ip address is a home and office use.
2.PUBLIC IP
Internet services provider home and office.
### TCP AND UDP
The main rule  that computer use to send data across the internet.
TCP check for lost data, making it slow but safe.
UDP sends data fast without checking.
### PORT 
Port is a type of door computer.different servics different door.
PORT        COMMON USE
22           SSH
53           DNS
80           HTTP
443          HTTPS
3389         RDP
### DNS (DOMAIN NAME SYSYTEM)
DNS is the phone book of the internet.it is translates names ,like google.com.
### HTTPS/TLS 
HTTPS/TLS Internet your computer between website secure/encrypted. any other people not read data.

## Commands I Ran
'commands I ran'means the computer instructions,codes,terminal tasks that you already executed or typed in the past.

### Ping google.com
To test your network connectivity using google, the standard command you need to type into your command line or terminal is ping google.com

### dig google.com
this is a command network used to quary domain name system name server.
it gathers information about host addresses,mail exchange,and name servers.

### curl -v https://example.com
check your computer connect the website
curl-send a request
-v- show the detail information
https://example.com-the website you are connecting to.

### Listening Ports
Find out which network ports on your mac are currently waiting for incoming computer

### traceroute google.com
see the network path your computer takes to reach google's server
it display multiple hops. a hop is basically one network device/route along the path.
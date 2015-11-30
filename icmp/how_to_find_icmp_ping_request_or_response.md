## The Internet Control Message Protocol (ICMP)
##### Question 2 : How to find icmp ping request or response?
```bash
$ tshark -i eth0 -Y "icmp.type==8 || icmp.type==0"
```

###### REFERENCE:

* [IANA - Internet Control Message Protocol (ICMP) Parameters](https://www.iana.org/assignments/icmp-parameters/icmp-parameters.xhtml)
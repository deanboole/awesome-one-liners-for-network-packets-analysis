## Transport Layer Security (TLS)/ Secure Socket Layer (SSL) Protocol
##### Question : How to find tls/ssl server hello message?
```bash
$ tshark -i "eth0" -Y "ssl.handshake.type==2"
```

###### REFERENCE:

* [Wikipedia -  Transport Layer Security]
(https://en.wikipedia.org/wiki/Transport_Layer_Security)
* [Wireshark Wiki - Secure Socket Layer (SSL)]
(https://wiki.wireshark.org/SSL)
* [Display Filter Reference: Secure Sockets Layer]
(https://www.wireshark.org/docs/dfref/s/ssl.html)

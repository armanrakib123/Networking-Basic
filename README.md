# Networking-Basic

* What is encapsulation
* Link layer
  * Link layer basics (pick something like Ethernet to get a quick overview of what the link layer entails)
  * What is a MAC address
* IP - this is a vast topic but there are several important concepts to understand here
  * IP addresses and subnet masks
  * How are IP addresses different from MAC addresses and why are they required
  * How do you discover a MAC address of a device on the same network if you only have its IP address (hint: see ARP)
  * What are routers and how IP routing works
  * Route tables
  * IP fragmentation
  * TTL
  * How ping and traceroute work
  * IPv6, why its required and why has its adoption been slow
* Transport layer
  * What is a port number and why is it required
  * UDP
  * TCP
    * Connection establishment (three way handshake)
    * Connection termination
    * Data transfer
    * Reliable transmission
    * Flow control (sliding window)
    * Congestion control
    * Error detection
    * Maximum segment size (MSS) and its relation with IP fragmentation
    * Selective acknowledgements (SACK) and how they help
    * When should you use TCP instead of UDP and vice versa?
* DNS
  * How it works - does it use UDP, TCP or something else?
  * What are root name servers and how do DNS resolvers works starting from the root
  * What is the nameserver (NS) of a domain?
  * Different types of records
    * A
    * AAAA
    * CNAME
    * MX
    * TXT
    * NS
  * DNS-over-HTTPS and why browsers have started using it
* HTTP
  * Request
    * Request line (method + path + query params + HTTP version)
    * Headers
    * Body
  * Response
    * Status line
    * Headers
    * Body
  * Safe methods v/s idempotent methods
  * When to use GET vs POST vs PUT
  * Cookies
  * Authentication
  * Content types
    * application/x-www-form-urlencoded
    * text/html
    * text/plain
    * application/json
    * Content types for images and other documents
  * Multi part requests
  * Chunked encoding
  * Compression
  * Why is the `Host` header required?
  * Connection re-use and request pipeline
  * Overview of HTTP/2 and HTTP/3
* TLS
  * No need to go into details of TLS but understand the basics
  * What are X509 certificates and how does a client use them and a certificate authority to authenticate the server
  * What is asymmetric encryption and how it is used in TLS
  * What is Diffie Helman key exchange
  * When does symmetric encryption (like AES) come into play in a TLS connection
  * SNI
* HTTP
  * Understand the relationship between TCP, TLS and HTTP - especially how HTTP is built on top of TCP/TLS and the guarantees that the underlying protocols provide (e.g. stream of bytes, etc.)
  * What is HTTP proxying and how it works
  * CDNs and how they reduce network latency
* HTTPS
  * Difference between HTTP and HTTPS
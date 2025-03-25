This script useful for bypassing WAFs/CDNs , identifying misconfigurations , discovering exposed services. 

- Resolves domains to IP addresses
- Scans each IP for direct HTTP/HTTPS access on common ports
- Sends the request with the correct HOST Header
- Supports custom DNS resolvers 

Running script:
- chmod +x ip_http_scanner
- sudo cp ip_http_scanner /usr/local/bin
- ./ip_http_scanner -r resolvers.txt targets.txt

# Lulzbuster 

Lulzbuster is a highly efficient and intelligent web directory and file enumeration tool written in C. It provides fast and comprehensive scanning capabilities to aid in the process of information gathering during penetration testing engagements. By utilizing Lulzbuster, you can identify hidden directories and files on web servers, uncovering potential vulnerabilities and valuable information.

## Features

- Fast and efficient web directory and file enumeration
- Support for various HTTP request types
- Customizable HTTP options, including user-agent strings, headers, and authentication credentials
- Follows HTTP redirects
- Timeout options for delay, connect, and request timeouts
- Tuning options for concurrent scanning and connection cache size
- Wordlist-based scanning with the ability to append custom words
- Proxy support with authentication credentials
- Insecure mode to skip SSL/TLS certificate verification
- Smart mode for eliminating false-positives and providing additional information
- Customizable nameservers for DNS resolution
- Logging of found paths and valid URLs

## Usage

```
lulzbuster -s https://failsame.ru/ -w /usr/share/lulzbuster/lists/big.txt
```

For more details and examples, please refer to the [official Lulzbuster repository](https://github.com/noptrix/lulzbuster).
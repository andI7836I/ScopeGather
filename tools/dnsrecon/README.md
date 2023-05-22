# DNSRecon

DNSRecon is a powerful command-line tool used for DNS reconnaissance during penetration testing engagements. It is designed to gather valuable information about the target's DNS infrastructure, discover subdomains, perform zone transfers, and identify potential misconfigurations or vulnerabilities.

## Installation

To install DNSRecon, follow these steps:

1. Clone the repository:
```
git clone https://github.com/darkoperator/dnsrecon
```
2. Navigate to the DNSRecon directory:
```
cd dnsrecon
```

3. Install the required dependencies:
```
python3 setup.py
```

## Usage

DNSRecon offers various features and options for conducting comprehensive DNS reconnaissance. Here are some examples of common usage:

- Discover subdomains of a target domain:
```
dnsrecon -d example.com -t brt
```

- Perform a zone transfer against a specific DNS server:
```
dnsrecon -d example.com -t axfr -s nameserver.example.com
```
- Bruteforce subdomains using a custom wordlist:
```
dnsrecon -d example.com -t brt -w wordlist.txt
```

These are just a few examples of how DNSRecon can be used. For more detailed information on available options and usage examples, refer to the official DNSRecon documentation or run `dnsrecon --help`.
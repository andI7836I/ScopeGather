# dnscan

dnscan is a powerful reconnaissance tool used for gathering subdomains and discovering DNS information about a target domain. It helps penetration testers and security researchers identify potential entry points and vulnerabilities in a company's infrastructure.

## Features

- Subdomain enumeration: dnscan uses various techniques, including DNS queries, zone transfers, and brute-forcing, to enumerate subdomains associated with the target domain.
- DNS information retrieval: The tool collects DNS-related information such as IP addresses, MX records, NS records, and CNAME records for the discovered subdomains.
- Extensive scanning capabilities: dnscan supports multi-threading and provides options for customizing the scan parameters, allowing you to perform efficient and thorough reconnaissance.

## Installation

To install dnscan, follow these steps:

1. Clone the dnscan repository from GitHub:
```
git clone https://github.com/rbsec/dnscan
```
2. Change into the dnscan directory:
```
cd dnscan
```
3. Install the required Python dependencies:
```
pip install -r requirements.txt
```

## Usage

1. Run dnscan by specifying the target domain:
```
python dnscan.py -d example.com -w subdomains-500.txt
```

Replace `example.com` with the domain you want to scan.

2. dnscan will start enumerating subdomains and collecting DNS information. The progress and results will be displayed in the terminal.

3. Once the scan is complete, dnscan will generate a report containing the discovered subdomains and their associated DNS information.

For more detailed usage instructions and available options, please refer to the [dnscan GitHub repository](https://github.com/rbsec/dnscan).
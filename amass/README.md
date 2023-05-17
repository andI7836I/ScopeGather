# Amass

Amass is an open-source reconnaissance tool used for network mapping and information gathering during penetration testing engagements. It leverages various techniques, such as DNS enumeration, web scraping, and API interactions, to discover and map the attack surface of target organizations.

## Features

- **DNS Enumeration**: Amass performs DNS enumeration to identify subdomains associated with the target domain. It supports multiple data sources, including brute forcing, zone transfers, and certificate transparency logs.
- **Web Scraping**: The tool employs web scraping techniques to collect data from websites, including subdomain information, email addresses, and network-related details.
- **API Integrations**: Amass integrates with various external APIs, such as threat intelligence platforms, to gather additional intelligence and enrich the reconnaissance process.
- **Active Enumeration**: The tool performs active enumeration techniques, such as port scanning, to identify open ports and services running on target hosts.

## Installation

### Kali Linux


```
sudo apt install amass
```

### Ubuntu
```
sudo snap install amass
```

## Usage

Amass provides a wide range of functionalities and options for reconnaissance and information gathering. Here are some common use cases and commands:

Perform a basic enumeration of a target domain:


```
amass enum -d example.com
```

Use passive DNS to discover subdomains:
```
amass intel -d example.com
```

Utilize active scanning techniques to discover additional assets:
```
amass enum -d example.com -active
```
Perform a full-blown enumeration with aggressive options:
```
amass enum -d example.com -brute -active -o output.txt
```
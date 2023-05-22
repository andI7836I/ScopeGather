# Subfinder

Subfinder is a powerful subdomain discovery tool used for gathering information during penetration testing and reconnaissance activities. It is designed to identify subdomains associated with a target domain, providing valuable insights into the target's online presence and potential attack vectors.

## Description

Subfinder leverages various techniques, including DNS brute-forcing, search engine scraping, and certificate transparency logs, to enumerate subdomains for a given target domain. By discovering these subdomains, you can uncover potential entry points and vulnerabilities that can be exploited.

## Installation

To install Subfinder, follow this command:
```
go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
```
## Usage

Subfinder provides a flexible command-line interface that allows you to customize your subdomain enumeration process. Here is an example of how to use Subfinder:
```
subfinder -d example.com
```
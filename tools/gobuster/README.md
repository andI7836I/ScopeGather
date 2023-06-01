# Gobuster

Gobuster is a powerful open-source tool used for directory and subdomain brute-forcing during penetration testing engagements. It is designed to discover hidden paths and directories on web servers, allowing you to identify potential vulnerabilities and uncover sensitive information.

## Installation

   ```
   go install github.com/OJ/gobuster/v3@latest
   ```
## Usage

Gobuster can be executed with various options and flags to customize its behavior according to your testing requirements. Here is a basic example of how to use Gobuster:

```
gobuster dir -u <target_url> -w <wordlist_path> -t <threads>
```

* -u <target_url>: Specify the target URL or IP address to be scanned.
* -w <wordlist_path>: Specify the path to the wordlist file containing directories and paths to brute-force.
* -t <threads>: Set the number of concurrent threads to be used during the scan.

For more advanced usage and additional command-line options, please refer to the [official Gobuster documentation](https://github.com/OJ/gobuster).
# WPScan

WPScan is a powerful command-line tool designed for WordPress security testing and vulnerability scanning. It is specifically developed to identify security weaknesses in WordPress installations, plugins, and themes. WPScan is widely used by penetration testers and security professionals to assess the security posture of WordPress websites.

## Installation

To install WPScan, follow these commands:
```
sudo apt install ruby-full
sudo gem install wpscan
```
To update WPScan:
```
wpscan --update
```

## Usage

WPScan provides a wide range of options and features to facilitate comprehensive WordPress security assessments. Here are some common usage examples:

To scan a specific WordPress website, use the following command:
```
wpscan --url <target URL>
```

Replace <target URL> with the URL of the WordPress website you want to scan.

To perform an aggressive scan that includes plugin and theme enumeration, run:
```
wpscan --url <target URL> --enumerate p,t
```
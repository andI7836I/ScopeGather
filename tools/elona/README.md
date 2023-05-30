# Enola

Enola is a modern, shiny command-line tool written in Golang that helps you hunt down social media accounts by username across various social networks. It is inspired by Sherlock and serves as its sister tool, offering similar functionality with a fresh interface and improved performance.

## Features

- Username search: Enola enables you to search for a specific username across multiple social media platforms simultaneously.
- Comprehensive results: The tool retrieves and presents detailed information about discovered accounts, including profile names, URLs, and additional metadata.
- Wide social network coverage: Enola supports a wide range of popular social media networks, ensuring broad coverage for your search.
- CLI simplicity: The command-line interface of Enola makes it easy to use, with intuitive commands and clear output.

## Installation

To use Enola, you need to have Golang installed on your system. Once you have Golang set up, you can install Enola by following these steps:

```
go install github.com/theyahya/enola/cmd/enola@latest
```

## Usage

```
enola {username}
```
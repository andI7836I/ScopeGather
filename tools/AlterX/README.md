# AlterX

AlterX is a powerful tool designed for generating subdomain wordlists quickly and easily. It utilizes a Domain-Specific Language (DSL) to provide extensive customization options, allowing users to tailor their wordlists to specific target domains.
Features


# Installation

```
go install github.com/projectdiscovery/alterx/cmd/alterx@latest
```

# Usage

INPUT:
-l, -list string[]     subdomains to use when creating permutations (stdin, comma-separated, file)

-p, -pattern string[]  custom permutation patterns input to generate (comma-seperated, file)

-pp, -payload value    custom payload pattern input to replace/use in key=value format (-pp 'word=words.txt')

OUTPUT:
-es, -estimate      estimate permutation count without generating payloads

-o, -output string  output file to write altered subdomain list

-v, -verbose        display verbose output

-silent             display results only

-version            display alterx version

CONFIG:
-config string  alterx cli config file (default '$HOME/.config/alterx/config.yaml')

-en, -enrich    enrich wordlist by extracting words from input

-ac string      alterx permutation config file (default '$HOME/.config/alterx/permutation_v0.0.1.yaml')

-limit int      limit the number of results to return (default 0)


UPDATE:
-up, -update                 update alterx to latest version

-duc, -disable-update-check  disable automatic alterx update check
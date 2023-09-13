# Heave blocklist

Lists that are used by services provided by Heave to block access to certain websites.

We are open to any PRs that add new lists or improve existing ones.

## Lists

> Lists are collected from various repositories and sources. We do not own any of the lists.

- Adult - `https://raw.githubusercontent.com/heavelabs/blocklist/main/lists/adult.txt`
- Gambling - `https://raw.githubusercontent.com/heavelabs/blocklist/main/lists/gamble.txt`
- Crypto - `https://raw.githubusercontent.com/heavelabs/blocklist/main/lists/crypto.txt`
- Piracy - `https://raw.githubusercontent.com/heavelabs/blocklist/main/lists/piracy.txt`

## Format

- The format of the lists is one domain per line.
- The domains are not prefixed with `www.`.
- The domains are not prefixed with `http://` or `https://`.
- The domains are not suffixed with `/`.
- All subdomains can be blocked by adding `.domain.com` to the list (the base domain will be blocked as well).

## Sources

- [StevenBlack/hosts](https://github.com/StevenBlack/hosts)
- [blocklistproject/lists](https://github.com/blocklistproject/lists)

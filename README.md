Domainguesser tries to find subdomains for a given domain. If a subdomain is
found its IP address is looked up. Stolen from "Black Hat Go: 5 Exploiting
DNS".

```
$ go install

$ domainguesser -domain example.com -wordlist wordlist.txt
www.example.com    93.184.216.34
```
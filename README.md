Domainguesser tries to find subdomains for a given domain. If a subdomain is
found its IP address is looked up. Adapted from "Black Hat Go: 5 Exploiting
DNS".

```
$ go install

$ domainguesser < wordlist.txt -d perlmonks.org
ads.perlmonks.org	66.39.54.27
css.perlmonks.org	209.197.123.153
css.perlmonks.org	216.92.34.251
css.perlmonks.org	66.39.54.27
ns4.perlmonks.org	209.197.123.153
ns4.perlmonks.org	216.92.34.251
ns4.perlmonks.org	66.39.54.27
www.perlmonks.org	66.39.54.27
www.perlmonks.org	209.197.123.153
www.perlmonks.org	216.92.34.251
www1.perlmonks.org	66.39.54.27
www2.perlmonks.org	209.197.123.153
```

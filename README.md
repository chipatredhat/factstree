# factstree
Display gathered ansible facts in an interactive tree

This is a simple script which gathers ansible facts from a host and uses the jtree python module to display them in an interactive window

Copy this script to your system, make it executeable, and optionally pass a hostname if you wish to gather facts from a host other than localhost

### Quickstart
```
curl -sO https://raw.githubusercontent.com/chipatredhat/factstree/refs/heads/main/factstree
chmod +x factstree
./factstree
```
or
```
./factstree <hostname>
```

***NOTES:*** 
- If you are not in a location that is configured to use your ansible inventory file, and you try to pass a hostname, this will fail
- The script will check if you have the necessary jtree python module installed and prompt you with directions on how to install it if not found

# factstree
Display gathered ansible facts in an interactive tree using the jtree python module

Copy this script to your system, make it executeable, and optionally pass a hostname or use localhost as default

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

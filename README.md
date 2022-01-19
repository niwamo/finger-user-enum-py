# finger-user-enum-py
Basic Implementation of pentestmonkey/finger-user-enum in Python. Improved speed and output formatting.

```
usage: finger-user-enum.py [-h] [-q] [-t THREADCOUNT] [-o OUT] userfile rhost

positional arguments:
  userfile        wordlist to use for potential usernames
  rhost           ip address of target host

optional arguments:
  -h, --help      show this help message and exit
  -q              suppress running output
  -t THREADCOUNT
  -o OUT          path to output file
```
  
![example output](https://github.com/nm2438/finger-user-enum-py/raw/main/example.png "Example Output")

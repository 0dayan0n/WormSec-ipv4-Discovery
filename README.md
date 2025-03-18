We need to set next three positional arguments to the script:
-target (aboutme.info)
-target_list List of ranges (0.0.0.0/16,6.1.0.0 etc . . .)
-match (<title>Welcome to aboutme.info</title>)
Also we can set optional arguments as timeout, threads, uri, etc…

One Line command: python3 real_ip_discover.py "www.cisco.com" 0.0.0.0/24 "<title>Cisco"

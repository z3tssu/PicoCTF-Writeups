# GET aHEAD

## Overview

Points: 20
Category: Web Exploitation

## Description

> Find the flag being held on this server to get ahead of the competition http://mercury.picoctf.net:28916/
## Hints

1. Maybe you have more than 2 choices
2. Check out tools like Burpsuite to modify your requests and look at the responses

## Approach

BurpSuite is Required for this CTF
1. Burpsuite works on 127.0.0.1 and port 8080
2. Configure Firefox Proxy to use 127.0.0.1 and port 8080 for HTTP
3. Open Burpsuite > Options > Enable "Receive Responce"
4. When Pressing the RED Option
5. View the Request that comes in
6. Change the GET to a HEAD 
7. then Forward the packer
8. the CTF Flag will be shown.

```

## Flag

picoCTF{r3j3ct_th3_du4l1ty_70bc61c4}

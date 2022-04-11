# Nice netcat

## Overview

Points: 20
Category: General

## Description

> Can you look at the data in this binary: static? This BASH script might help!
## Hints

None

## Approach

We can simply use strings and grep to find the flag this time:

strings static | grep pico

```

## Flag

picoCTF{d15a5m_t34s3r_1e6a7731}


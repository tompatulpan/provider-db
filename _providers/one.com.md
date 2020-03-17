---
name: one.com
status: OK
domains: 
  - one.com
server:
  # Repeat the following block for each server (usually one for imap, one for smtp).
  - type: IMAP
    socket: SSL
    hostname: imap.one.com
    port: 993
  - type: smtp
    socket: SSL
    hostname: send.one.com
    port: 465
last_checked: 2020-03
website: one.com
---

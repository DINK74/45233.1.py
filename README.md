# Exploit: OpenSSH 7.7 - Username Enumeration
## Author: Justin Gardner
Date: 2018-08-20

Software: https://ftp4.usa.openbsd.org/pub/OpenBSD/OpenSSH/openssh-7.7.tar.gz

Affected Versions: OpenSSH version < 7.7

CVE: CVE-2018-15473

## Author: Krzysztof Wlodarski
Date: 2022-10-24

Description: changes needed to run under Python 3

1. replaced tab indent character with spaces at original line 35
2. added parentheses () to print statements
3. replaced _handler_table with _client_handler_table at original lines 30, 104, 105

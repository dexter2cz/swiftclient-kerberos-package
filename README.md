#swiftclient-kerberos-package
**Very dirty all-in-one debian package for python-swiftclient with Kerberos authentication support.**<br />

Make debian package
=======
Clone and run swiftclient-kerberos-package script to make debian package. You can install it via dpkg -i after.

Using swift client:
======
 1. All parametrs in one line, you can omit -U and -K when --kerberos is present
swift --kerberos -A https://server:8080/auth/1.0 list<br />

 2. set environment variables
export ST_AUTH="https://server:8080/auth/1.0"
swift --kerberos list<br />
or<br />
export ST_KRB=1
swift list

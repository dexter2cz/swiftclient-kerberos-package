#swiftclient-kerberos-package
Very dirty all-in-one debian package for python-swiftclient with Kerberos authentication support.<br />
Usage:<br />
swift --kerberos -A https://server:8080/auth/1.0 list<br />
or<br />
export ST_AUTH="https://server:8080/auth/1.0"<br />
swift --kerberos list<br />
or<br />
export ST_KRB=1<br />
swift list<br />

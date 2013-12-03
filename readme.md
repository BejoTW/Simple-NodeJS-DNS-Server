#Simple NodeJS DNS Server

Requirements:

* nodejs needs to be installed. On debian, use aptitude install nodejs or download via nodejs.org
* native-dns. This can be installed using npm install on the command line, assuming you have npm installed (http://npmjs.org)

Running the test:

Server:
    
    node DNSServer.js
    
User Clinet:

    >nslookup
    >server x.x.x.x
    >www.google.com
    
    Output
    > www.google.com
    Server:		10.5.161.106
    Address:	10.5.161.106#53
    
    Non-authoritative answer:
    Name:	www.google.com
    Address: 74.125.23.103
    Name:	www.google.com
    Address: 74.125.23.104
    Name:	www.google.com
    Address: 74.125.23.99
    Name:	www.google.com
    Address: 74.125.23.147
    Name:	www.google.com
    Address: 74.125.23.106
    Name:	www.google.com
    Address: 74.125.23.105
    > trailers.apple.com
    Server:		10.5.161.106
    Address:	10.5.161.106#53

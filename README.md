Javascript CouchDB Integration POC
==================================

This is meant to be an example integration app to demonstrate javascript integration with couch.

###Prerequisites
Make sure python is installed on Ubuntu box. Before running following commands:

```
	sudo apt-get install python-setuptools
	easy_install couchdb
	easy_install simplejson
	easy_install couchapp

```

###Installing
Make sure couch db is insttalled and running on 5984 port. Instructions can be found here: http://guide.couchdb.org/draft/unix.html

1. Clone this repository
```
    git clone https://github.com/techhorn/jsCouchIntegration
    cd jsCouchIntegration
```

###Running
```
    couchapp push . http://localhost:5984/jsCouchIntegration
```

###Access the application
```
http://127.0.0.1:5984/jsCouchIntegration/_design/jsCouchIntegration/index.html
```



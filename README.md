Web Notification Sytem 
=======================

The application is a web based **Push** notification system.

User will post listings of the items. Other users who are interested in that particular listing can shortlist and place offer on that product. Upon shortlisting, system will send notifications to users who have shortlisted that product earlier. Also, upon placing an order, system will send notifications to both the users who have shortlisted the product,placed an offer on that product and the owner of the product. These notifications are Push based (realtime) notifications implemented using node.js and socket.io.

We’re going to build a Django application, using the following packages, python and node.js modules:

* python
* python-virtualenv
* redis-server
* nginx (from the official Nginx ppa)
* nodejs (from Chris Leas’s ppa)
* npm, socket.io and cookie
* django
* django-user-sessions
* celery

npm packages to be installed with the project:

1. cookie
2. redis
3. socket.io
4. socket.io-redis
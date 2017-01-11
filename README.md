# Nginx with SSL - Opentracker 

This is the config file for Nginx and the makefile for OpenTracker

* [OpenTracker](http://erdgeist.org/arts/software/opentracker/) - Lightly Torrent Tracker Open Source
* [Nginx](https://www.nginx.com/resources/wiki/) - Http(s) Server

OpenTracker need to use access.whitelist and use TCP: 
...
listen.tcp 0.0.0.0
access.whitelist = hash.list
...

### Versions

...
0.0.1:	* Worked !
	  
...






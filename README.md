WLoggerDaemon is a mac daemon (background application) that connects with USB to some weather stations from Oregon Scientifics. It currently works with WMR100, WMRS200, RMS300 and RMS600. WLoggerDaemon logs data to [CouchDB](http://couchdb.apache.org) and/or sends Twitter updates every hour.

NB! The current implementation saves passwords in a prefs file, so don't use your most valuable secrets. I will change this ASAP.
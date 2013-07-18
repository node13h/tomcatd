tomcatd
=======

Apache Tomcat instance manager

Manages multiple tomcat instances on single server.
Each instance is run on system startup under specified UID 
with it's own JAVA/CATALINA settings.

Tested with Tomcat 5.5, but should work with later versions.

See opt/conf.d/example.conf

Don't forget to run chkconfig --add tomcatd


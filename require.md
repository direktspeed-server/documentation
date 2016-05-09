# !!! WARNING THIS IS NOT LIVE !!!
# !!! Still in Alpha not complet ported to github"

## How to start 




# Production http installation
npm install dssrv dssrv-http dssrv-prefork

## modules for server
- dssrv-http // gives http protocol support for listen 
- dssrv-net // gives tcp&udp/ip protocol support for listen
- dssrv-ws // gives socket.io / ws protocol support for listen
- dssrv- option to define own protocols and handlers 

# dssrv 
the main engine it creates the inital Object wich is a instance of dssrv

# dssrv-install
Templates for installing dssrv for diffrent usecases

# dssrv-prefork
It will supply you with a command to start use dssrv object with a .js file it will be used 
supplys options for how often it should prefork the jsfile 
the js file can make use of all dssrv options

# dssrv options
.listen() // host and port and all that and vhost and protocol 
.head // middelware all this stuff




# dssrv-tools-nginx
Gives you some tools to import and use config files can parse the syntax and include files all like normal
for easy adoption
will also install required modules if needed: dssrv dssrv-http dssrv-proxy

# dssrv-tools-apache
Gives you some tools to import and use config files can parse the syntax and include files all like normal
for easy adoption
will also install required modules if needed: dssrv dssrv-http dssrv-proxy

# dssrv-tools-lhttpd

# dssrv-tools-haproxy
# dssrv-tools-varnish
# dssrv-migrator 
toolset to migrate existing servers to dssrv for replacment.

# dssrv-mysql
gives you the mysql protocol to listen to and also adds lb and caching and proxy with readwrite split support via its sub modules
dssrv-mysql-proxy, dssrv-mysql-lb, dssrv-mysql-cache




# dssrv-host
Will allow host configuration for dssrv modules.








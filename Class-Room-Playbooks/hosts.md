172.31.24.180

**************************************************

172.31.24.180
localhost

**************************************************

172.31.24.180
172.31.24.181
dev.internal.qt.com

***************************************************

172.31.24.180
localhost

[ubuntu]
172.31.24.180
Localhost

# from here([ubuntu]) to till next square bracket([centos]) is ubuntu

[centos]
20.121.55.193
172.31.24.180
localhost

***************************************************************

[ubuntu]
172.31.24.180
localhost

[centos]
20.121.55.193

[webservers] 
web[01:10].qt.com # means web01.qt.com, web02.qt.com.....web10.qt.com

**********************************************************************

172.31.24.180
localhost

[ubuntu]
172.31.24.180 name=node1
localhost name=acn

[centos]
20.121.55.193 name=node2

[webservers]
web[01:10].qt.com

***********************************************************************

[ubuntu]
172.31.24.180 name=node1
localhost name=acn

[centos]
20.121.55.193 name=node2

[webservers]
20.121.55.193 name=node2
172.31.24.180 name=node1

***********************************************************************

[ubuntu]
172.31.24.180 name=node1
localhost name=acn  group=none

[centos]
20.121.55.193 name=node2

[webservers]
20.121.55.193 name=node2
172.31.24.180 name=node1

[webserver:vars]
group=webserver
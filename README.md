# uptimekuma


## About

uptime kuma is a self host monitoring tool.
It can monitor a website using its url. I can monitor uptime using http,tcp,ping, dns and other mechanism too.
mostly we will be using it via docker/ container.

## Install

use docker command to run uptime kuma

`docker run -d --restart-always -p 3001:3001 -v uptime-kuma:/app/data --name uptime-kuma louislam/uptime-kuma:1`
uptime kuma will be running on `http://localhost:3001`
NFS not supported.


we can monitor the url of website and we can use authentication and authorization.

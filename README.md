
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **7674** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|121|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|121|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|121|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1926|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1197|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3300|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|138.201.132.168|8118|Germany|Falkenstein|Hetzner Online GmbH|
|2|148.251.150.106|3128|Germany|Falkenstein|Hetzner Online GmbH|
|3|47.242.126.227|8001|Hong Kong|Hong Kong|Alibaba.com LLC|
|4|179.96.28.58|80|Brazil|São Paulo|G8 NETWORKS LTDA|
|5|181.215.178.58|1337|Netherlands|Amsterdam|NovoServe B.V.|
|6|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|7|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|8|135.148.95.28|3128|United States|Reston|OVH SAS|
|9|135.148.95.28|3128|United States|Reston|OVH SAS|
|10|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|11|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|12|47.251.15.176|1080|United States|Santa Clara|Alibaba.com LLC|
|13|45.152.188.248|3128|United States|Ashburn|Sprint|
|14|75.126.253.8|8080|United States|Dallas|SoftLayer|
|15|8.29.103.131|8080|United States|Dawsonville|North Georgia Network Cooperative, Inc|
|16|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|17|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|18|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|19|45.8.179.241|1337|United Kingdom|London|HOSTLAND|
|20|70.177.15.10|8080|United States|Gilbert|Cox Communications Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


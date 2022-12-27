
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5179** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|280|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|280|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|280|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|813|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|257|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2858|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|2|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|3|157.230.217.232|8080|United States|North Bergen|DigitalOcean, LLC|
|4|18.159.181.93|8081|Germany|Frankfurt am Main|Amazon.com, Inc.|
|5|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|6|47.254.156.107|8000|Germany|Frankfurt am Main|Alibaba.com LLC|
|7|23.109.172.148|9090|Netherlands|Amsterdam|SERVERS-COM|
|8|142.4.215.171|3128|Canada|Beauharnois|OVH SAS|
|9|164.92.185.195|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|10|157.230.217.226|8080|United States|North Bergen|DigitalOcean, LLC|
|11|203.150.128.100|8080|Thailand|Watthana|Internet Thailand Company Ltd|
|12|159.192.249.93|8080|Thailand|Bangkok|CAT-BB|
|13|34.84.142.87|3128|Japan|Tokyo|Google LLC|
|14|182.53.201.253|8080|Thailand|Chanthaburi|TOT Public Company Limited|
|15|34.146.64.228|3128|Japan|Tokyo|Google LLC|
|16|40.85.152.26|8080|United States|San Francisco|Microsoft Corporation|
|17|47.243.121.74|3128|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|18|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|19|134.238.252.143|8080|India|Mumbai|Google LLC|
|20|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


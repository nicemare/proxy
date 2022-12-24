
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5545** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|503|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|503|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|503|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1176|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|576|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2842|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.42.177.39|3128|United States|Ashburn|Sprint|
|2|5.161.90.204|3128|United States|Ashburn|Hetzner Online GmbH|
|3|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|4|45.70.236.194|999|Ecuador|Puebloviejo|Nedetel S.A.|
|5|185.247.224.124|8118|Romania|Bucharest|Flokinet Ltd|
|6|45.42.177.39|3128|United States|Ashburn|Sprint|
|7|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|8|45.87.43.167|3128|Netherlands|Amsterdam|SpectraIP B.V.|
|9|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|149.129.223.129|3128|Indonesia|Jakarta|Alibaba.com Singapore E-Commerce Private Limited|
|12|147.139.190.205|3128|Indonesia|Jakarta|Alibaba.com LLC|
|13|35.200.4.163|3128|Japan|Tokyo|Google LLC|
|14|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|15|4.246.220.253|8080|United States|Boydton|Microsoft Corporation|
|16|146.190.125.150|3128|United States|San Francisco|DigitalOcean, LLC|
|17|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|18|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|19|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|20|3.86.90.249|3128|United States|Ashburn|Amazon Technologies Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


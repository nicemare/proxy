
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5678** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|405|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|405|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|405|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1093|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|554|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2780|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|2|50.114.128.17|3128|Pakistan|Karachi|Delta Centric LLC, Comcast Cable Communications, LLC|
|3|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|4|184.105.182.254|3128|United States|Gilroy|Hurricane Electric LLC|
|5|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|6|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|7|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|8|45.8.179.241|1337|United Kingdom|London|HOSTLAND|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|11|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|12|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|13|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|14|45.8.179.242|1337|United Kingdom|London|HOSTLAND|
|15|149.129.255.38|3128|Indonesia|Jakarta|Alibaba.com Singapore E-Commerce Private Limited|
|16|142.129.238.249|80|United States|Pomona|Charter Communications Inc|
|17|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|18|147.139.190.169|3128|Indonesia|Jakarta|Alibaba.com LLC|
|19|173.47.77.210|80|United States|Boise|Cable ONE|
|20|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


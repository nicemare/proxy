
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5182** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|429|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|429|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|429|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|817|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|539|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2575|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|172.120.119.209|9527|United States|Santa Clara|EGIHosting|
|4|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|
|5|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|
|6|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|7|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|8|161.35.223.141|80|Germany|Frankfurt am Main|DigitalOcean, LLC|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|134.122.58.174|80|Netherlands|Amsterdam|DigitalOcean, LLC|
|11|172.120.119.209|9527|United States|Santa Clara|EGIHosting|
|12|94.130.72.212|44440|Germany|Nuremberg|Hetzner Online GmbH|
|13|149.129.255.38|3128|Indonesia|Jakarta|Alibaba.com Singapore E-Commerce Private Limited|
|14|176.99.2.43|1081|Russia|Moscow|"Domain names registrar REG.RU", Ltd|
|15|147.139.191.118|3128|Indonesia|Jakarta|Alibaba.com LLC|
|16|190.63.35.30|9812|Ecuador|Ambato|CONECEL|
|17|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|18|178.217.172.206|55443|Kyrgyzstan|Bishkek|KRENA - Kyrgyz research and education network association|
|19|147.139.190.169|3128|Indonesia|Jakarta|Alibaba.com LLC|
|20|147.139.191.249|3128|Indonesia|Jakarta|Alibaba.com LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


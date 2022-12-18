
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4855** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|364|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|364|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|364|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|912|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|323|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2669|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|40.85.152.26|8080|United States|San Francisco|Microsoft Corporation|
|5|40.85.152.26|8080|United States|San Francisco|Microsoft Corporation|
|6|119.8.236.97|3128|Hong Kong|Hong Kong|Huawei International Pte. Ltd.|
|7|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|8|45.234.60.50|999|Venezuela|San Antonio de Los Altos|SOLUCIONES INSTALRED CH&C C.A.|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|51.159.115.233|3128|France|Paris|SCALEWAY|
|11|45.125.217.90|5555|Hong Kong|Hong Kong|PINGNET|
|12|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|15|95.217.88.72|40050|Finland|Helsinki|Hetzner Online GmbH|
|16|183.88.192.20|8080|Thailand|Pak Kret|Triple T Broadband Public Company Limited|
|17|110.78.186.232|8080|Thailand|Chachoengsao|CAT-BB|
|18|209.146.19.58|55443|Philippines|Manolo Fortich|Cogent Communications|
|19|190.2.210.234|999|Colombia|Piamonte|TV AZTECA SUCURSAL COLOMBIA|
|20|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


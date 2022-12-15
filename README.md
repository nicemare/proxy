
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **7462** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|420|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|420|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|420|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1623|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1288|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3300|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|132.147.34.22|8111|United States|Miami|Breezeline|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|89.58.10.16|3129|Germany|Nuremberg|netcup GmbH|
|5|45.152.188.248|3128|United States|Ashburn|Sprint|
|6|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|7|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|8|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|9|51.159.115.233|3128|France|Paris|SCALEWAY|
|10|135.148.95.28|3128|United States|Reston|OVH SAS|
|11|181.143.106.162|52151|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|12|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|13|45.152.188.248|3128|United States|Ashburn|Sprint|
|14|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|15|182.253.141.237|8080|Indonesia|Semarang|Biznet Networks|
|16|192.155.95.228|10000|United States|Atlanta|Linode, LLC|
|17|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|18|134.238.252.143|8080|India|Mumbai|Google LLC|
|19|75.126.253.8|8080|United States|Dallas|SoftLayer|
|20|109.165.112.94|3128|Russia|Semikarakorsk|BRAS Huawei ME60 (128kusers)|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


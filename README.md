
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5736** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|384|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|384|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|384|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1113|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|622|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2718|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|4|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|5|51.159.115.233|3128|France|Paris|SCALEWAY|
|6|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|7|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|75.126.253.8|8080|United States|Dallas|SoftLayer|
|10|212.119.215.13|3128|Russia|Moscow|PJSC "Vimpelcom"|
|11|47.244.2.19|3128|Hong Kong|Central|Alibaba.com LLC|
|12|195.178.197.20|8080|Russia|Podolsk|IIP|
|13|45.23.54.102|8888|United States|St Louis|AT&T Services, Inc.|
|14|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|15|110.74.195.34|25|Cambodia|Phnom Penh|EZECOM limited|
|16|200.25.254.193|54240|Colombia|Bogotá|Andinet ON Line|
|17|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|18|103.31.109.59|3128|Indonesia|Ciwedus|Koperasi PRIMKOKAS|
|19|114.132.165.163|9999|China|Shijiazhuang|CNC Group CHINA169 Hebei Province network|
|20|31.7.67.127|3128|Iran|Tehran|Asiatech Data Transmission company|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


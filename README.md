
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **7274** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|331|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|331|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|331|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1928|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1277|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2718|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|2|47.243.167.134|8889|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|3|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|4|190.63.35.30|9812|Ecuador|Ambato|CONECEL|
|5|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|6|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|7|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|8|103.152.232.194|8080|Indonesia|Subang|PT Kingpolah Network Solutions|
|9|51.159.115.233|3128|France|Paris|SCALEWAY|
|10|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|11|213.136.101.36|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|
|12|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|13|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|14|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|15|216.169.73.65|34679|United States|Cedar City|South Central Communications, Inc.|
|16|212.80.213.94|8080|Thailand|Nonthaburi|Siamdata Communication Co.|
|17|207.188.11.31|80|United States|San Antonio|H5 Data Centers - Chandler LLC|
|18|94.103.85.88|9300|Russia|Moscow|VDSINA|
|19|134.238.252.143|8080|India|Mumbai|Google LLC|
|20|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


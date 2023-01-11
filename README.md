
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6400** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|414|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|414|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|414|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1516|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|808|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2725|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|47.243.167.134|8889|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|2|134.238.252.143|8080|India|Mumbai|Google LLC|
|3|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|6|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|7|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|8|45.8.179.242|1337|United Kingdom|London|Hostland LLC|
|9|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|10|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|11|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|12|45.8.179.247|1337|United Kingdom|London|Hostland LLC|
|13|212.80.213.94|8080|Thailand|Nonthaburi|Siamdata Communication Co.|
|14|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|
|15|5.58.110.249|8080|Ukraine|Ternopil|Columbus|
|16|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|17|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|18|201.238.248.139|9229|Chile|Santiago|Gtd Internet S.A|
|19|138.2.29.85|3128|Japan|Tokyo|Oracle Corporation|
|20|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


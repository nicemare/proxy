
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5110** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|549|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|549|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|549|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|685|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|484|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2690|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|5|135.148.95.28|3128|United States|Reston|OVH SAS|
|6|75.126.253.8|8080|United States|Dallas|SoftLayer|
|7|135.148.95.28|3128|United States|Reston|OVH SAS|
|8|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|9|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|10|148.251.150.106|3128|Germany|Falkenstein|Hetzner Online GmbH|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|134.238.252.143|8080|India|Mumbai|Google LLC|
|13|92.241.102.47|3128|Russia|Khislavichi|SMOLTELECOM|
|14|43.231.0.40|7890|Hong Kong|Victoria|BUILDCLOUD|
|15|5.195.40.27|8080|United Arab Emirates|Sharjah|Emirates Telecommunications Corporation|
|16|201.219.11.205|999|Ecuador|Quito|Corporacion Nacional De Telecomunicaciones - CNT EP|
|17|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|18|189.164.110.242|10101|Mexico|Puebla City|Uninet S.A. de C.V|
|19|173.47.77.210|80|United States|Boise|Cable ONE|
|20|89.107.197.165|3128|Russia|Tula|LLC TK Altair|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


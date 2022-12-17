
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **7204** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|542|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|542|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|542|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1767|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1105|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3081|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|149.56.233.29|3128|Canada|Montreal|OVH Hosting|
|2|51.159.115.233|3128|France|Paris|SCALEWAY|
|3|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|4|54.175.209.233|80|United States|Ashburn|Amazon.com, Inc.|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|7|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|8|59.124.62.9|3128|Taiwan|Taipei|Chunghwa Telecom Co., Ltd.|
|9|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|10|43.153.202.48|80|Singapore|Singapore|Aceville Pte.ltd|
|11|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|12|54.175.209.233|80|United States|Ashburn|Amazon.com, Inc.|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|103.147.246.129|8080|Indonesia|Serang|PLBNET|
|15|223.205.72.101|8080|Thailand|Nong Chok|Triple T Broadband Public Company Limited|
|16|52.26.227.50|80|United States|Portland|Amazon.com, Inc.|
|17|5.39.105.211|3128|France|Lyon|OVH SAS|
|18|14.248.115.131|19132|Vietnam|Hanoi|VNPT|
|19|103.114.52.75|3127|Indonesia|Sukoharjo|Proxy-registered|
|20|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


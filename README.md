
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5918** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|539|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|539|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|539|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1204|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|568|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2895|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|51.159.115.233|3128|France|Paris|SCALEWAY|
|3|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|4|179.96.28.58|80|Brazil|Calcilandia|G8 NETWORKS LTDA|
|5|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|
|6|45.8.179.242|1337|United Kingdom|London|HOSTLAND|
|7|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|8|75.126.253.8|8080|United States|Dallas|SoftLayer|
|9|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|10|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|11|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|12|190.45.251.189|3128|Chile|Santiago|VTR BANDA ANCHA S.A.|
|13|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|14|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|15|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|16|103.141.108.122|8080|Indonesia|Blitar|Data Buana Nusantara|
|17|158.69.27.94|9300|Canada|Montreal|OVH SAS|
|18|116.101.227.80|3333|Vietnam|Hung Yen|Viettel Corporation|
|19|190.63.35.30|9812|Ecuador|Ambato|CONECEL|
|20|105.174.7.254|8080|Angola|Luanda|UNITEL SA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


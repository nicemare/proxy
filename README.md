
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5873** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|535|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|535|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|535|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1177|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|620|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2825|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|3|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|4|47.240.1.7|27954|Hong Kong|Central|Alibaba.com LLC|
|5|140.227.61.156|23456|Japan|Chiyoda-ku|InfoSphere|
|6|134.122.58.174|80|Netherlands|Amsterdam|DigitalOcean, LLC|
|7|80.66.81.40|8080|Ukraine|Odesa|Shulzhenko Bohdana Valentynivna|
|8|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|212.46.230.102|6969|Russia|Moscow|PJSC "Vimpelcom"|
|11|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|12|147.139.191.249|3128|Indonesia|Jakarta|Alibaba.com LLC|
|13|167.114.96.27|9300|Canada|Montreal|OVH SAS|
|14|181.113.225.178|80|Ecuador|Guayaquil|Corporacion Nacional De Telecomunicaciones - CNT EP|
|15|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|16|187.216.90.46|53281|Mexico|Cabo San Lucas|Uninet S.A. de C.V.|
|17|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|18|185.218.126.155|39811|Germany|Düsseldorf|Contabo GmbH|
|19|85.94.81.194|8080|Croatia|Zagreb|Terrakom d.o.o.|
|20|87.255.12.183|3129|Russia|Khimki|BIG TELECOM CLOSED JSC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


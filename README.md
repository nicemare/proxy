
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6568** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|514|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|514|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|514|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|2028|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|533|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2756|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|135.148.95.28|3128|United States|Reston|OVH SAS|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|6|143.198.82.124|8081|Singapore|Singapore|DigitalOcean, LLC|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|54.151.6.61|3128|United States|San Jose|Amazon.com, Inc.|
|9|109.194.101.128|3128|Russia|Yoshkar-Ola|CJSC "ER-Telecom Holding" Yoshkar-Ola branch|
|10|75.126.253.8|8080|United States|Dallas|SoftLayer|
|11|116.0.61.122|3128|Pakistan|Karachi|Telecard|
|12|135.148.95.28|3128|United States|Reston|OVH SAS|
|13|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|14|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|15|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|16|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|17|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|18|167.114.96.27|9300|Canada|Montreal|OVH SAS|
|19|179.1.95.171|999|Colombia|Neiva|InterNexa Global Network|
|20|95.111.239.49|3131|Germany|Nuremberg|Contabo GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


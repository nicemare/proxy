
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5585** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|409|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|409|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|409|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|949|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|692|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2693|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|4|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|5|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|6|80.66.81.40|8080|Ukraine|Odesa|Shulzhenko Bohdana Valentynivna|
|7|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|158.69.53.98|9300|Canada|Montreal|OVH SAS|
|10|190.152.5.17|39888|Ecuador|Guayaquil|Corporacion Nacional De Telecomunicaciones - CNT EP|
|11|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|12|101.109.176.144|8080|Thailand|Ban Khao Yoi|TOT Public Company Limited|
|13|213.136.101.36|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|
|14|192.155.95.228|10755|United States|Atlanta|Linode, LLC|
|15|192.155.95.228|10755|United States|Atlanta|Linode, LLC|
|16|200.85.169.18|47548|Nicaragua|Managua|IBW Communications|
|17|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|18|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|19|183.221.242.103|9443|China|Mianyang|China Mobile|
|20|186.96.148.144|999|Mexico|Zacapoaxtla|Total Play Telecomunicaciones SA De CV|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


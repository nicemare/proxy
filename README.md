
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6005** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|735|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|735|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|735|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1108|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|809|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2837|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|51.159.115.233|3128|France|Paris|SCALEWAY|
|4|80.66.81.40|8080|Ukraine|Odesa|Shulzhenko Bohdana Valentynivna|
|5|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|6|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|7|94.130.72.212|44440|Germany|Nuremberg|Hetzner Online GmbH|
|8|207.180.216.251|8118|Germany|Nuremberg|Contabo GmbH|
|9|75.126.253.8|8080|United States|Dallas|SoftLayer|
|10|172.120.119.209|9527|United States|Santa Clara|EGIHosting|
|11|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|12|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|13|66.211.155.34|8080|United States|Milford|FirstLight Fiber|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|16|176.196.250.86|3128|Russia|Kemerovo|Goodline.info|
|17|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|18|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|19|103.242.119.88|80|India|Kolkata|Web Werks India Pvt. Ltd.|
|20|213.136.101.40|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


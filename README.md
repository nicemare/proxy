
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6184** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|616|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|616|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|616|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|987|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|663|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3283|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|135.148.95.28|3128|United States|Reston|OVH SAS|
|2|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|3|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|4|5.39.105.211|3128|France|Lyon|OVH SAS|
|5|135.148.95.28|3128|United States|Reston|OVH SAS|
|6|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|7|51.195.19.222|3131|Germany|Limburg an der Lahn|OVH SAS|
|8|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|9|192.155.95.228|10801|United States|Atlanta|Linode, LLC|
|10|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|13|45.8.179.241|1337|United Kingdom|London|HOSTLAND|
|14|191.103.219.225|48612|Colombia|Montería|Edatel S.a. E.S.P|
|15|134.238.252.143|8080|India|Mumbai|Google LLC|
|16|190.63.35.30|9812|Ecuador|Ambato|CONECEL|
|17|202.181.14.23|3128|Bangladesh|Dhaka|BDPEER|
|18|188.17.117.126|3128|Russia|Chelyabinsk|LLC "KomTehCentr"|
|19|103.180.135.55|10000|Vietnam|Hanoi|Httvserver Technology Company Limited|
|20|45.8.179.242|1337|United Kingdom|London|HOSTLAND|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


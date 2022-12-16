
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5309** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|525|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|525|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|525|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|841|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|733|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2784|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|135.148.95.28|3128|United States|Reston|OVH SAS|
|2|5.39.105.211|3128|France|Lyon|OVH SAS|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|54.151.6.61|3128|United States|San Jose|Amazon.com, Inc.|
|5|135.148.95.28|3128|United States|Reston|OVH SAS|
|6|164.92.73.145|3128|United States|Santa Clara|DigitalOcean, LLC|
|7|164.92.73.145|3128|United States|Santa Clara|DigitalOcean, LLC|
|8|54.151.6.61|3128|United States|San Jose|Amazon.com, Inc.|
|9|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|10|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|11|134.238.252.143|8080|India|Mumbai|Google LLC|
|12|179.49.144.210|3128|Brazil|Macaé|Meganet Telecomumicacoes Ltda|
|13|190.63.35.30|9812|Ecuador|Ambato|CONECEL|
|14|157.100.12.138|999|Ecuador|Alamor|Telconet S.A|
|15|43.231.0.40|7890|Hong Kong|Victoria|BUILDCLOUD|
|16|185.123.101.174|4443|Turkey|Bursa|DGN TEKNOLOJI A.S.|
|17|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|18|166.104.231.44|8888|South Korea|Ansan-si|Hanyang University|
|19|51.79.50.22|9300|Canada|Beauharnois|OVH SAS|
|20|51.159.115.233|3128|France|Paris|SCALEWAY|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


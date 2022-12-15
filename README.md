
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4545** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|392|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|392|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|392|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|834|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|315|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2445|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|2|14.32.188.144|8080|South Korea|Seoul|Korea Telecom|
|3|135.148.95.28|3128|United States|Reston|OVH SAS|
|4|192.155.95.228|10000|United States|Atlanta|Linode, LLC|
|5|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|6|75.126.253.8|8080|United States|Dallas|SoftLayer|
|7|135.148.95.28|3128|United States|Reston|OVH SAS|
|8|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|9|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|10|43.231.0.40|7890|Hong Kong|Victoria|BUILDCLOUD|
|11|154.16.180.182|3128|United States|Dulles|LYIT Internet Services|
|12|154.16.180.182|3128|United States|Dulles|LYIT Internet Services|
|13|189.164.23.18|10101|Mexico|Puebla City|Uninet S.A. de C.V|
|14|45.189.254.150|999|Mexico|Santiago Tuxtla|Wantelco SAS de CV|
|15|8.29.103.131|8080|United States|Dawsonville|North Georgia Network Cooperative, Inc|
|16|103.161.119.102|10000|Vietnam|Ho Chi Minh City|THIENCO|
|17|178.128.57.159|8081|Singapore|Singapore|DigitalOcean, LLC|
|18|209.146.19.115|55443|Philippines|Butuan|Cogent Communications|
|19|47.251.15.176|1080|United States|Santa Clara|Alibaba.com LLC|
|20|134.238.252.143|8080|India|Mumbai|Google LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


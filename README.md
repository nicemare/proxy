
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5093** proxies at the latest update. Usable proxies are below.

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|831|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|478|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2533|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|45.152.188.248|3128|United States|Ashburn|Sprint|
|3|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|4|47.251.15.176|1080|United States|Santa Clara|Alibaba.com LLC|
|5|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|6|45.152.188.248|3128|United States|Ashburn|Sprint|
|7|47.251.15.176|1080|United States|Santa Clara|Alibaba.com LLC|
|8|114.43.80.189|3128|Taiwan|Taipei|Chunghwa Telecom Co., Ltd.|
|9|135.148.95.28|3128|United States|Reston|OVH SAS|
|10|149.28.132.3|8000|Singapore|Singapore|The Constant Company|
|11|75.126.253.8|8080|United States|Dallas|SoftLayer|
|12|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|13|135.148.95.28|3128|United States|Reston|OVH SAS|
|14|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|15|134.238.252.143|8080|India|Mumbai|Google LLC|
|16|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|17|88.99.204.242|3128|Germany|Nuremberg|Hetzner Online GmbH|
|18|164.92.73.145|3128|United States|Santa Clara|DigitalOcean, LLC|
|19|109.165.112.94|3128|Russia|Semikarakorsk|BRAS Huawei ME60 (128kusers)|
|20|118.99.101.167|8080|Indonesia|Jakarta|Biznet Metronet|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


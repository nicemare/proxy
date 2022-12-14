
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4526** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|226|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|226|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|226|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|649|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|277|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2349|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|135.148.95.28|3128|United States|Reston|OVH SAS|
|3|47.251.15.176|1080|United States|Santa Clara|Alibaba.com LLC|
|4|45.152.188.248|3128|United States|Ashburn|Sprint|
|5|181.78.65.234|999|Colombia|Bogotá|IFX Networks Argentina S.R.L|
|6|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|7|164.92.73.145|3128|United States|Santa Clara|DigitalOcean, LLC|
|8|77.247.126.194|3128|United States|Los Angeles|Clouvider Limited|
|9|135.148.95.28|3128|United States|Reston|OVH SAS|
|10|38.49.135.250|999|Mexico|Celaya|Ientc S De RL De CV|
|11|164.92.73.145|3128|United States|Santa Clara|DigitalOcean, LLC|
|12|5.187.2.186|8089|Germany|Frankfurt am Main|First Colo via AS44066|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|75.126.253.8|8080|United States|Dallas|SoftLayer|
|15|77.247.126.194|3128|United States|Los Angeles|Clouvider Limited|
|16|47.251.15.176|1080|United States|Santa Clara|Alibaba.com LLC|
|17|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|18|20.239.27.216|3128|Hong Kong|Hong Kong|Microsoft Corporation|
|19|184.82.232.58|8080|Thailand|Bangkok|AIS-Fibre|
|20|88.99.204.242|3128|Germany|Nuremberg|Hetzner Online GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


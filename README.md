
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5253** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|416|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|416|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|416|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|849|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|568|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2585|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|47.251.15.176|1080|United States|Santa Clara|Alibaba.com LLC|
|2|201.77.109.126|999|Mexico|Ocampo|Nidix Networks S.a. De C.V.|
|3|159.89.132.167|8989|United States|Santa Clara|DigitalOcean, LLC|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|6|180.183.27.226|8080|Thailand|Hat Yai|Triple T Broadband Public Company Limited|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|190.43.92.20|999|Peru|Tacna|Telefonica Del Peru|
|9|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|10|14.32.188.144|8080|South Korea|Seoul|Korea Telecom|
|11|103.247.22.46|8080|Indonesia|Bekasi|PT wifian Solution|
|12|180.183.88.242|8080|Thailand|Bang Lamung|Triple T Broadband Public Company Limited|
|13|183.89.97.118|8080|Thailand|Bang Bua Thong|Triple T Broadband Public Company Limited|
|14|38.49.135.249|999|Mexico|Celaya|Ientc S De RL De CV|
|15|125.27.75.11|8080|Thailand|Ban Bueng|TOT Public Company Limited|
|16|118.174.93.166|8081|Thailand|Bang Phli|TOT Public Company Limited|
|17|203.32.21.250|3128|Turkey|Bursa|DGN TEKNOLOJI A.S.|
|18|75.126.253.8|8080|United States|Dallas|SoftLayer|
|19|36.80.100.113|8080|Indonesia|Bandung|PT. TELKOM INDONESIA|
|20|103.161.112.109|10000|Vietnam|Ho Chi Minh City|Viet Digital Technology Liability Company|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5440** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|444|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|444|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|444|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|907|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|537|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2745|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|135.148.95.28|3128|United States|Reston|OVH SAS|
|2|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|135.148.95.28|3128|United States|Reston|OVH SAS|
|5|51.159.115.233|3128|France|Paris|SCALEWAY|
|6|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|7|54.151.6.61|3128|United States|San Jose|Amazon.com, Inc.|
|8|164.92.73.145|3128|United States|Santa Clara|DigitalOcean, LLC|
|9|187.204.35.179|53281|Mexico|Tamazula de Gordiano|Uninet S.A. de C.V.|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|13|116.96.122.2|4001|Vietnam|Phu Ly|Viettel Corporation|
|14|101.109.107.203|8080|Thailand|Ban Nong Sala|TOT Public Company Limited|
|15|183.88.0.33|8080|Thailand|Nakhon Ratchasima|Triple T Broadband Public Company Limited|
|16|125.25.33.112|8080|Thailand|Chiang Mai|TOT Public Company Limited|
|17|46.101.13.77|80|United Kingdom|London|DigitalOcean, LLC|
|18|192.155.95.228|10801|United States|Atlanta|Linode, LLC|
|19|45.233.67.230|999|Guatemala|Jalapa|Conectividad Y Tecnologia S.A|
|20|5.187.2.186|8089|Germany|Frankfurt am Main|First Colo via AS44066|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


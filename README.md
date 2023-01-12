
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6058** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|425|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|425|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|425|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1183|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|748|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2776|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|51.159.115.233|3128|France|Paris|SCALEWAY|
|3|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|4|190.2.210.238|999|Colombia|Piamonte|TV AZTECA SUCURSAL COLOMBIA|
|5|45.32.69.105|3128|United States|Los Angeles|The Constant Company|
|6|217.64.14.180|8080|Czechia|Brno|GiTy, a.s.|
|7|217.64.14.162|8080|Czechia|Brno|GiTy, a.s.|
|8|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|9|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|10|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|11|103.164.116.170|8080|Indonesia|Malang|SOLUSINET|
|12|134.238.252.143|8080|India|Mumbai|Google LLC|
|13|45.32.69.105|3128|United States|Los Angeles|The Constant Company|
|14|34.146.19.255|3128|Japan|Tokyo|Google LLC|
|15|91.243.192.26|8080|Ukraine|Moshny|"Fregat TV" Ltd.|
|16|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|17|45.179.246.129|999|Colombia|Acevedo|Genionet Telecomunicaciones|
|18|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|19|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|20|111.68.26.237|8080|Indonesia|Ngupasan|GMEDIA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


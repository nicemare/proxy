
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5922** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|255|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|255|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|255|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1206|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|853|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2812|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|2|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|3|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|6|212.14.243.29|8080|Palestine|Nablus|PALTEL (Palestine Telecommunications Co.).|
|7|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|8|112.78.161.217|8080|Indonesia|Jakarta|Biznet Networks|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|11|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|12|103.92.26.190|4002|Vietnam|Ho Chi Minh City|TLSOFT|
|13|161.77.218.163|3129|United States|Springfield|Crocker Communications|
|14|45.91.133.137|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|15|109.194.22.112|3128|Russia|Irkutsk|CJSC "ER-Telecom Holding" Irkutsk branch|
|16|125.25.32.129|8080|Thailand|Chiang Mai|TOT Public Company Limited|
|17|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|18|206.127.254.245|3129|United States|Glendale|Spartan Host Ltd|
|19|45.166.144.3|999|Chile|Santiago|Fullsolution S.P.A.|
|20|219.148.43.102|3128|China|Beijing|Chinanet|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


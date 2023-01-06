
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6080** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|472|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|472|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|472|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1294|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|626|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2809|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|179.96.28.58|80|Brazil|Calcilandia|G8 NETWORKS LTDA|
|2|143.198.193.27|443|Singapore|Singapore|DigitalOcean, LLC|
|3|207.5.79.174|3128|United States|Roseville|Network Innovations|
|4|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|5|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|6|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|7|109.194.101.128|3128|Russia|Yoshkar-Ola|CJSC "ER-Telecom Holding" Yoshkar-Ola branch|
|8|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|9|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|10|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|11|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|12|210.245.124.131|5239|Vietnam|Ho Chi Minh City|FPT Telecom Company|
|13|182.253.109.87|8080|Indonesia|Semarang|Biznet Metronet|
|14|203.115.106.85|8080|India|Greater Noida|PRIMENET|
|15|138.2.8.164|8000|Japan|Tokyo|Oracle Corporation|
|16|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|17|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|18|52.53.251.113|3128|United States|San Jose|Amazon.com, Inc.|
|19|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|20|103.167.68.82|8080|Indonesia|Margahayukencana|PT Kataji Nukami Indonesia|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


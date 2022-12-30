
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5906** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|403|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|403|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|403|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1158|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|668|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2729|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|142.4.215.171|3128|Canada|Beauharnois|OVH SAS|
|2|198.46.143.114|8118|Canada|Hamilton|ColoCrossing|
|3|34.84.72.91|3128|Japan|Tokyo|Google LLC|
|4|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|5|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|6|198.46.143.114|8118|Canada|Hamilton|ColoCrossing|
|7|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|8|31.6.69.119|3999|Poland|Tarnowskie Gory|Livenet sp. z o.o.|
|9|178.33.198.181|3128|France|Strasbourg|OVH SAS|
|10|47.242.174.100|8000|Hong Kong|Hong Kong|Alibaba.com LLC|
|11|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|12|182.253.141.189|8080|Indonesia|Semarang|Biznet Networks|
|13|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|16|179.96.28.58|80|Brazil|Calcilandia|G8 NETWORKS LTDA|
|17|103.56.206.65|4995|Indonesia|Jakarta|Argon Data Communication|
|18|158.51.107.253|8080|United States|Fredericksburg|4 ip Technology and Media, LLC|
|19|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|20|103.79.77.30|8888|United States|Los Angeles|QuadraNet Enterprises LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5972** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|405|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|405|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|405|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1218|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|604|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2799|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|2|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|3|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|4|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|5|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|6|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|7|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|8|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|9|192.210.196.65|9090|United States|San Jose|ColoCrossing|
|10|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|11|134.238.252.143|8080|India|Mumbai|Google LLC|
|12|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|13|159.192.249.98|8080|Thailand|Bangkok|CAT-BB|
|14|139.59.241.101|443|Singapore|Singapore|DigitalOcean, LLC|
|15|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|16|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|17|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|18|23.82.16.149|3128|United States|San Jose|Leaseweb USA, Inc.|
|19|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|20|23.106.47.29|3128|United States|New York|Leaseweb USA, Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4571** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|200|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|200|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|200|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|882|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|241|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2165|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|2|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|3|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|4|117.251.103.186|8080|India|Hazratpur|BSNL Internet|
|5|180.183.6.175|8080|Thailand|Bang Lamung|Triple T Broadband Public Company Limited|
|6|94.45.137.34|8080|Ukraine|Kyiv Oblast|Kievline LLC|
|7|110.78.186.181|8080|Thailand|Chachoengsao|CAT-BB|
|8|140.227.61.156|23456|Japan|Chiyoda|InfoSphere|
|9|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|10|20.151.25.71|3128|Canada|Toronto|Microsoft Corporation|
|11|89.107.197.165|3128|Russia|Tula|LLC TK Altair|
|12|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|
|13|23.106.47.29|3128|United States|New York|Leaseweb USA, Inc.|
|14|204.185.204.64|8080|United States|Kansas City|org-morenet.more.net|
|15|47.186.44.66|1080|United States|Plano|Frontier Communications Solutions|
|16|190.26.201.194|8080|Colombia|Bogotá|ETB - Colombia|
|17|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|18|172.105.225.236|31330|Japan|Tokyo|Linode, LLC|
|19|209.166.175.201|8080|United States|Pittsburgh|CONTINENTAL BROADBAND PENNSYLVANIA, INC.|
|20|111.225.153.7|8089|China|Gaocheng|Chinanet|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5158** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|397|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|397|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|397|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|986|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|533|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2688|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.42.177.99|3128|United States|Ashburn|Sprint|
|2|142.4.215.171|3128|Canada|Beauharnois|OVH SAS|
|3|45.42.177.39|3128|United States|Ashburn|Sprint|
|4|23.109.172.148|9090|Netherlands|Amsterdam|SERVERS-COM|
|5|45.42.177.99|3128|United States|Ashburn|Sprint|
|6|45.42.177.39|3128|United States|Ashburn|Sprint|
|7|185.247.224.124|8118|Romania|Bucharest|Flokinet Ltd|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|10|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|11|179.189.172.100|8080|Brazil|Rio de Janeiro|Rede Brasileira de Comunicacao S/A|
|12|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|13|171.97.116.233|8080|Thailand|Chiang Mai|True Internet Corporation CO. Ltd.|
|14|182.253.73.130|80|Indonesia|Labansari|BIZNET|
|15|74.115.139.196|80|United States|Humboldt|Infostructure Cable and Internet|
|16|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|17|74.115.139.196|80|United States|Humboldt|Infostructure Cable and Internet|
|18|14.161.31.192|53281|Vietnam|Ho Chi Minh City|VNPT|
|19|103.161.97.229|10000|Vietnam|Hà Đông|MXGROUP|
|20|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


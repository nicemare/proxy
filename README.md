
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5907** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|504|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|504|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|504|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1346|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|580|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2630|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|2|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|3|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|4|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|5|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|6|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|7|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|8|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|9|130.185.225.240|3128|Bulgaria|Sofia|Telepoint Ltd|
|10|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|11|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|12|34.84.56.140|3128|Japan|Tokyo|Google LLC|
|13|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|14|207.5.79.174|3128|United States|Roseville|Network Innovations|
|15|159.223.14.199|443|Netherlands|Amsterdam|DigitalOcean, LLC|
|16|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|17|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|18|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|19|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|20|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6560** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|302|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|302|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|302|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1502|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|801|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2906|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|2|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|3|129.213.183.152|80|United States|Ashburn|Oracle Corporation|
|4|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|5|109.206.252.234|80|Iran|Pardis County|Afagh Andish Dadeh Pardis Co. Ltd|
|6|206.127.254.245|3129|United States|Glendale|Spartan Host Ltd|
|7|129.213.183.152|80|United States|Ashburn|Oracle Corporation|
|8|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|9|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|10|138.2.8.164|8000|Japan|Tokyo|Oracle Corporation|
|11|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|12|141.147.158.11|8080|Japan|Osaka|Oracle Corporation|
|13|34.91.252.109|80|Netherlands|Groningen|Google LLC|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|16|137.184.154.110|443|United States|North Bergen|DigitalOcean, LLC|
|17|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|18|152.70.252.224|8080|South Korea|Seoul|Oracle Corporation|
|19|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|20|200.106.187.242|999|Argentina|Jose Maria Ezeiza|Fullnet Solutions S.A.S.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


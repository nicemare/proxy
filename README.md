
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5000** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|279|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|279|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|279|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|835|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|407|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2507|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.152.188.248|3128|United States|Ashburn|Sprint|
|2|185.81.98.17|3131|Netherlands|Naaldwijk|WorldStream B.V.|
|3|45.152.188.248|3128|United States|Ashburn|Sprint|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|201.219.201.14|999|Colombia|El Banco|ITELKOM|
|6|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|7|112.140.186.124|808|Singapore|Singapore|Sparkstation Pte Ltd|
|8|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|9|116.98.185.176|10000|Vietnam|Hanoi|Viettel Corporation|
|10|110.78.141.115|8080|Thailand|Samut Prakan|CAT-BB|
|11|202.56.163.110|8080|Indonesia|Jakarta|Varnion Technology Semesta|
|12|116.103.140.88|10000|Vietnam|Buon Ma Thuot|Viettel Corporation|
|13|5.160.179.8|8080|Iran|Tehran|Respina Networks & Beyond PJSC|
|14|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|15|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|16|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|17|52.45.139.115|80|United States|Ashburn|Amazon.com, Inc.|
|18|85.193.92.239|8118|Poland|Ełk|Artnet Sp. z o.o.|
|19|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|20|89.107.197.165|3128|Russia|Tula|LLC TK Altair|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


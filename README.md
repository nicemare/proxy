
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4314** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|223|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|223|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|223|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|433|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|253|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2345|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|94.45.137.34|8080|Ukraine|Kyiv Oblast|Kievline LLC|
|2|117.251.103.186|8080|India|Hazratpur|BSNL Internet|
|3|122.49.208.230|3128|Philippines|San Juan|WifiCity, Inc|
|4|4.233.217.137|8888|France|Paris|Microsoft Corporation|
|5|200.105.215.18|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|6|201.150.32.59|10605|Mexico|Mexico City|Servnet Mexico, S.A. de C.V.|
|7|122.49.208.242|3128|Philippines|San Juan|WifiCity, Inc|
|8|47.244.195.11|80|Hong Kong|Central|Alibaba.com LLC|
|9|187.50.25.130|8080|Brazil|São Paulo|Vivo|
|10|204.185.204.64|8080|United States|Kansas City|org-morenet.more.net|
|11|117.121.202.182|8088|Indonesia|Tegalsari|PT Sekawan Global Komunika|
|12|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|13|103.152.100.187|8080|Pakistan|Lahore|KK Networks (Pvt) Ltd.|
|14|54.88.125.126|9999|United States|Ashburn|Amazon.com, Inc.|
|15|117.251.103.186|8080|India|Hazratpur|BSNL Internet|
|16|54.88.125.126|9999|United States|Ashburn|Amazon.com, Inc.|
|17|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|18|148.101.179.182|8080|Dominican Republic|Santo Domingo Este|Compañía Dominicana de Teléfonos S. A|
|19|93.86.63.73|8080|Serbia|Belgrade|TELEKOM-SRBIJA|
|20|103.1.93.184|55443|Nepal|Kathmandu|Classic Tech Pvt. Ltd|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


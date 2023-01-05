
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5612** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|413|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|413|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|413|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1201|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|697|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2663|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|51.159.115.233|3128|France|Paris|SCALEWAY|
|2|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|3|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|4|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|5|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|6|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|7|164.70.122.6|3128|Japan|Yono|InfoSphere|
|8|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|9|51.79.50.22|9300|Canada|Beauharnois|OVH SAS|
|10|190.152.5.17|39888|Ecuador|Guayaquil|Corporacion Nacional De Telecomunicaciones - CNT EP|
|11|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|12|210.245.124.131|5239|Vietnam|Ho Chi Minh City|FPT Telecom Company|
|13|144.217.240.185|9300|Canada|Beauharnois|OVH SAS|
|14|68.183.185.62|80|Singapore|Singapore|DigitalOcean, LLC|
|15|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|16|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|17|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|18|110.34.3.229|3128|Nepal|Kathmandu|SUBISU C7|
|19|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|20|82.165.184.53|80|Germany|Frankfurt am Main|IONOS SE|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


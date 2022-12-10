
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5367** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|519|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|519|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|519|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1025|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|479|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2612|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|3|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|177.141.99.50|8080|Brazil|São Paulo|Claro NXT Telecomunicacoes Ltda|
|7|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|8|138.201.125.229|8118|Germany|Falkenstein|Hetzner Online GmbH|
|9|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|10|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|11|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|12|75.126.253.8|8080|United States|Dallas|SoftLayer|
|13|104.166.125.216|3128|United States|Los Angeles|Baxet Group Inc|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|200.125.170.74|999|Dominican Republic|Santiago de los Caballeros|WIRELESS MULTI SERVICE VARGAS CABRERA, S. R. L|
|16|108.61.73.183|3128|United States|Piscataway|The Constant Company|
|17|160.16.130.191|3128|Japan|Tokyo|SAKURA Internet Inc.|
|18|164.92.76.73|30007|United States|Santa Clara|DigitalOcean, LLC|
|19|201.150.119.136|999|Mexico|Actopan|Hulux Telecomunicaciones|
|20|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


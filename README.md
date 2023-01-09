
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6302** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|541|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|541|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|541|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1511|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|703|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2737|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|152.70.252.224|8080|South Korea|Seoul|Oracle Corporation|
|2|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|3|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|6|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|7|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|8|45.130.141.59|8080|United Kingdom|London|Bangmod Enterprise Co., Ltd.|
|9|34.84.56.140|3128|Japan|Tokyo|Google LLC|
|10|45.86.70.163|3333|United States|Los Angeles|DediPath|
|11|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|12|200.13.22.210|80|Mexico|Silao|Marcatel Com, S.A. de C.V.|
|13|85.14.243.31|3128|Germany|Kamp-Lintfort|myLoc managed IT AG|
|14|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|15|166.104.231.44|8888|South Korea|Ansan-si|Hanyang University|
|16|47.243.167.134|8889|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|17|212.80.213.94|8080|Thailand|Nonthaburi|Siamdata Communication Co.|
|18|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|19|45.86.70.163|3333|United States|Los Angeles|DediPath|
|20|167.172.148.49|3128|United States|North Bergen|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


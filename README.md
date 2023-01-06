
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6456** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|423|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|423|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|423|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1419|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1026|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2660|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|2|152.70.252.224|8080|South Korea|Seoul|Oracle Corporation|
|3|43.156.129.87|8080|Singapore|Singapore|Shenzhen Tencent Computer Systems Company Limited|
|4|185.198.61.146|3128|Italy|Milan|Global Router LLC|
|5|141.147.158.11|8080|Japan|Osaka|Oracle Corporation|
|6|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|7|83.41.71.8|8080|Spain|Palafrugell|Telefonica de Espana SAU|
|8|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|9|43.132.202.254|8080|Hong Kong|Hong Kong|Shenzhen Tencent Computer Systems Company Limited|
|10|216.238.66.39|3128|Mexico|Querétaro City|The Constant Company|
|11|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|12|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|13|126.125.62.15|8080|Japan|Fukuoka|Softbank BB Corp.|
|14|177.23.15.193|8080|Brazil|Tres de Maio|Sulnet Telecom|
|15|216.169.73.65|34679|United States|Cedar City|South Central Communications, Inc.|
|16|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|17|47.184.162.59|3128|United States|Garland|Frontier Communications Solutions|
|18|209.166.175.201|3128|United States|Pittsburgh|CONTINENTAL BROADBAND PENNSYLVANIA, INC.|
|19|188.6.135.118|8080|Hungary|Budapest|Magyar Telekom|
|20|173.212.200.30|3128|Germany|Nuremberg|Contabo GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


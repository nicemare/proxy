
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4098** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|96|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|96|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|96|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|391|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|192|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2132|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|121.173.30.180|8080|South Korea|Bucheon-si|Korea Telecom|
|2|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|3|193.122.71.184|3128|Saudi Arabia|Jeddah|Oracle Corporation|
|4|133.242.171.216|3128|Japan|Chiyoda|SAKURA Internet Inc.|
|5|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|6|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|7|47.252.4.64|8888|United States|Charlottesville|Alibaba.com LLC|
|8|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|9|89.208.219.121|8080|Netherlands|Amsterdam|My.com B.V.|
|10|185.213.27.227|3128|Germany|Düsseldorf|Contabo GmbH|
|11|122.155.165.191|3128|Thailand|Ratchathewi|CAT Telecom Public Company Limited|
|12|1.255.134.136|3128|South Korea|Gimhae|SK Broadband Co Ltd|
|13|185.252.28.242|3128|Iran|Tehran|Shabakeh Ertebatat Artak Towseeh LTD|
|14|103.142.111.106|8080|Indonesia|Makassar|PT. HIPERNET INDODATA|
|15|128.199.67.35|80|Singapore|Singapore|DigitalOcean, LLC|
|16|195.225.232.3|8085|Iran|Tehran|TS Information Technology Limited|
|17|74.208.51.100|80|United States|Knoxville|IONOS SE|
|18|181.37.241.178|8080|Dominican Republic|Santiago de los Caballeros|Altice Dominicana S.A.|
|19|209.166.175.201|8080|United States|Pittsburgh|CONTINENTAL BROADBAND PENNSYLVANIA, INC.|
|20|167.71.199.211|39667|Singapore|Singapore|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


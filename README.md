
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4393** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|204|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|204|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|204|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|435|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|268|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2307|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.134.235.132|3129|United States|Los Angeles|Corporate Colocation Inc|
|2|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|3|74.208.51.100|80|United States|Knoxville|IONOS SE|
|4|121.173.30.180|8080|South Korea|Bucheon-si|Korea Telecom|
|5|205.134.235.132|3129|United States|Los Angeles|Corporate Colocation Inc|
|6|74.208.51.100|80|United States|Knoxville|IONOS SE|
|7|204.185.204.64|8080|United States|Kansas City|org-morenet.more.net|
|8|204.185.204.64|8080|United States|Kansas City|org-morenet.more.net|
|9|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|10|23.106.47.29|3128|United States|New York|Leaseweb USA, Inc.|
|11|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|12|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|13|45.167.126.78|3128|Colombia|Popayán|Sepcom Comunicaciones SAS|
|14|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|
|15|85.14.243.31|3128|Germany|Kamp-Lintfort|myLoc managed IT AG|
|16|117.251.103.186|8080|India|Hazratpur|BSNL Internet|
|17|193.122.71.184|3128|Saudi Arabia|Jeddah|Oracle Corporation|
|18|187.130.139.197|8080|Mexico|Mexico City|Uninet S.A. de C.V.|
|19|103.157.96.97|3128|Indonesia|Jakarta|PT Beon Intermedia|
|20|195.225.232.3|8085|Iran|Tehran|TS Information Technology Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


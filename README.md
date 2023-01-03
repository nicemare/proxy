
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5754** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|406|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|406|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|406|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1281|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|570|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2552|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|96.68.234.217|8080|United States|Springfield|Comcast Cable Communications, LLC|
|2|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|3|96.68.234.217|8080|United States|Springfield|Comcast Cable Communications, LLC|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|6|23.95.186.182|3128|United States|Washington|ColoCrossing|
|7|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|8|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|9|149.28.132.9|10000|Singapore|Singapore|The Constant Company|
|10|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|11|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|12|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|13|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|14|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|15|173.219.112.85|8080|United States|Chicago|Suddenlink Communications|
|16|209.166.175.201|8080|United States|Pittsburgh|CONTINENTAL BROADBAND PENNSYLVANIA, INC.|
|17|198.229.231.13|8080|United States|Streator|MTCO Communications|
|18|191.242.230.135|8080|Brazil|Farroupilha|Domi Informatica|
|19|47.252.4.64|8888|United States|Charlottesville|Alibaba.com LLC|
|20|177.93.51.168|999|Colombia|Villavicencio|TV AZTECA SUCURSAL COLOMBIA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


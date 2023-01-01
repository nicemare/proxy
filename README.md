
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5839** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|556|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|556|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|556|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1326|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|682|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2780|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|2|45.8.179.242|1337|United Kingdom|London|Hostland LLC|
|3|51.159.115.233|3128|France|Paris|SCALEWAY|
|4|47.243.180.142|808|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|5|147.139.176.149|3128|Indonesia|Jakarta|Alibaba.com LLC|
|6|75.127.13.148|3128|United States|Seattle|ColoCrossing|
|7|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|8|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|
|9|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|10|159.203.31.27|8118|Canada|Toronto|DigitalOcean, LLC|
|11|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|12|138.2.8.164|8000|Japan|Tokyo|Oracle Corporation|
|13|147.139.192.225|3128|Indonesia|Jakarta|Alibaba.com LLC|
|14|75.127.13.148|3128|United States|Seattle|ColoCrossing|
|15|46.31.77.223|3128|Turkey|Gaziosmanpasa|Talha Bogaz|
|16|43.153.34.157|3128|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|17|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|18|178.33.198.181|3128|France|Strasbourg|OVH SAS|
|19|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|20|134.238.252.143|8080|India|Mumbai|Google LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


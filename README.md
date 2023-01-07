
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6282** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|409|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|409|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|409|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1402|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|783|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2746|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|2|149.56.95.184|80|Canada|Montreal|OVH Hosting|
|3|129.146.183.219|8080|United States|Phoenix|Oracle Corporation|
|4|128.14.140.2|11772|United States|Los Angeles|Zenlayer Inc|
|5|206.127.254.245|3129|United States|Glendale|Spartan Host Ltd|
|6|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|7|178.254.168.184|8080|United States|Los Angeles|Turkcell Internet|
|8|206.127.254.245|3129|United States|Glendale|Spartan Host Ltd|
|9|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|10|223.18.60.191|8080|Hong Kong|Central|HGC Global Communications Limited|
|11|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|12|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|15|134.122.58.174|80|Netherlands|Amsterdam|DigitalOcean, LLC|
|16|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|17|159.223.14.199|443|Netherlands|Amsterdam|DigitalOcean, LLC|
|18|95.216.230.239|80|Finland|Helsinki|Hetzner Online GmbH|
|19|164.92.178.35|80|Germany|Frankfurt am Main|DigitalOcean, LLC|
|20|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6188** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|435|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|435|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|435|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1611|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|691|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2835|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|2|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|3|159.223.14.199|443|Netherlands|Amsterdam|DigitalOcean, LLC|
|4|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|5|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|6|109.207.76.37|8080|Israel|Petah Tikva|O.M.C. COMPUTERS & COMMUNICATIONS LTD|
|7|143.198.56.234|443|United States|Santa Clara|DigitalOcean, LLC|
|8|45.8.179.241|1337|United Kingdom|London|Hostland LLC|
|9|34.146.64.228|3128|Japan|Tokyo|Google LLC|
|10|45.14.165.134|3128|United States|Reston|Delis LLC|
|11|183.88.135.127|8080|Thailand|Chiang Mai|Triple T Broadband Public Company Limited|
|12|110.78.208.91|8000|Thailand|Ratchathewi|CAT Telecom Public Company Limited|
|13|45.14.165.144|3128|United States|Reston|Delis LLC|
|14|203.150.128.117|8080|Thailand|Watthana|Internet Thailand Company Ltd|
|15|45.14.165.149|3128|United States|Reston|Delis LLC|
|16|47.244.2.19|3128|Hong Kong|Central|Alibaba.com LLC|
|17|45.14.165.149|3128|United States|Reston|Delis LLC|
|18|54.173.137.254|8090|United States|Ashburn|Amazon.com, Inc.|
|19|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|20|164.163.73.126|999|Honduras|Santa Rosa de Copán|Grupo Inma S.A|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


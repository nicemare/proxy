
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4204** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|92|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|92|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|92|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|440|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|174|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2339|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|172.104.128.235|8888|Germany|Frankfurt am Main|Linode, LLC|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|189.232.85.95|8080|Mexico|Tlaxcoapan|Uninet S.A. de C.V.|
|5|115.96.208.124|8080|India|Mumbai|Hathway IP over Cable Internet Access|
|6|18.118.71.69|3128|United States|Dublin|Amazon.com, Inc.|
|7|210.245.53.72|3128|Vietnam|Hanoi|FPT Telecom Company|
|8|165.192.111.151|3129|United States|Seattle|SoftLayer|
|9|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|10|101.109.176.145|8080|Thailand|Ban Pong Klang|TOT Public Company Limited|
|11|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|12|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|13|41.60.237.232|8080|Kenya|Nairobi|Maintainer Liquid Telecommunications Operations Limited|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|190.26.201.194|8080|Colombia|Bogotá|ETB - Colombia|
|16|122.155.165.191|3128|Thailand|Ratchathewi|CAT Telecom Public Company Limited|
|17|128.199.67.35|80|Singapore|Singapore|DigitalOcean, LLC|
|18|118.89.176.33|8118|China|Shenzhen|Shenzhen Tencent Computer Systems Company Limited|
|19|43.129.223.147|38080|Hong Kong|Hong Kong|Shenzhen Tencent Computer Systems Company Limited|
|20|45.167.125.97|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


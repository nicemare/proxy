
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5032** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|271|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|271|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|271|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|767|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|496|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2418|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|4|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|5|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|6|119.8.236.97|3128|Hong Kong|Hong Kong|Huawei International Pte. Ltd.|
|7|75.126.253.8|8080|United States|Dallas|SoftLayer|
|8|181.129.14.163|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|9|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|10|45.167.125.61|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|11|109.160.62.127|8080|Bulgaria|Nesebar|Vision 2008 Ltd|
|12|34.200.136.174|3128|United States|Ashburn|Amazon.com, Inc.|
|13|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|14|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|15|45.167.125.97|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|16|34.200.136.174|3128|United States|Ashburn|Amazon.com, Inc.|
|17|157.100.12.138|999|Ecuador|Loja|Telconet S.A|
|18|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|19|154.83.29.202|999|Venezuela|Caracas|internautas system|
|20|94.63.67.189|3128|Portugal|Lisbon|Vodafone Portugal|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5300** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|206|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|206|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|206|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|778|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|367|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2804|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|2|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|3|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|6|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|7|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|8|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|9|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|12|159.255.188.134|41258|Poland|Zamość|TOM-NET s.c. Dariusz Koper|
|13|159.255.188.134|41258|Poland|Zamość|TOM-NET s.c. Dariusz Koper|
|14|61.178.141.146|80|China|Yuzhong Chengguanzhen|Chinanet|
|15|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|16|49.176.208.135|8080|Australia|Sydney|SingTel Optus Pty Ltd|
|17|185.56.156.17|8080|Italy|Milan|HAL Service SpA|
|18|116.203.126.53|3128|Germany|Nuremberg|Hetzner Online GmbH|
|19|182.253.109.87|8080|Indonesia|Semarang|Biznet Metronet|
|20|183.172.81.32|7891|China|Haidian|CERNET|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


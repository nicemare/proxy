
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6256** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|480|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|480|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|480|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1255|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|811|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2839|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|129.146.183.219|8080|United States|Phoenix|Oracle Corporation|
|3|104.237.154.46|80|United States|Fremont|Linode, LLC|
|4|217.64.14.162|8080|Czechia|Brno|GiTy, a.s.|
|5|129.146.183.219|8080|United States|Phoenix|Oracle Corporation|
|6|200.119.89.19|80|Colombia|Bogotá|ETB - Colombia|
|7|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|8|104.237.154.46|80|United States|Fremont|Linode, LLC|
|9|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|10|45.130.141.59|8080|United Kingdom|London|Bangmod Enterprise Co., Ltd.|
|11|134.238.252.143|8080|India|Mumbai|Google LLC|
|12|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|13|77.41.146.14|8080|Russia|Moscow|OJSC Vimpelcom HQ|
|14|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|15|38.242.244.29|80|Germany|Düsseldorf|Contabo GmbH|
|16|152.70.252.224|8080|South Korea|Seoul|Oracle Corporation|
|17|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|18|83.171.236.79|8080|Germany|Schwielowsee|Droptop GmbH|
|19|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|20|185.255.46.121|8080|Iraq|Sulaymaniyah|Valin Company for General Trading and Communication LTD|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


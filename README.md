
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5284** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|252|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|252|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|252|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|971|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|552|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2410|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|2|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|3|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|4|47.243.180.142|808|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|5|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|6|65.21.161.114|42648|Finland|Helsinki|Hetzner Online GmbH|
|7|107.172.73.179|7890|United States|Buffalo|ColoCrossing|
|8|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|9|103.92.26.190|4002|Vietnam|Ho Chi Minh City|TLSOFT|
|10|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|11|192.151.146.242|3128|United States|Kansas City|Nocix, LLC|
|12|89.38.96.219|3128|Netherlands|Naaldwijk|WorldStream B.V.|
|13|1.255.134.136|3128|South Korea|Geoje|SK Broadband Co Ltd|
|14|61.178.141.146|80|China|Yuzhong Chengguanzhen|Chinanet|
|15|173.212.200.30|3128|Germany|Nuremberg|Contabo GmbH|
|16|188.40.20.151|3128|Germany|Falkenstein|Hetzner Online GmbH|
|17|51.158.154.173|3128|France|Paris|SCALEWAY|
|18|1.255.134.136|3128|South Korea|Geoje|SK Broadband Co Ltd|
|19|167.172.148.49|3128|United States|North Bergen|DigitalOcean, LLC|
|20|58.240.252.15|9001|China|Suzhou|CNC Group Jiangsu province network|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


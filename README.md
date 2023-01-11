
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6648** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|446|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|446|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|446|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1640|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|808|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2849|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|47.245.33.104|12345|Japan|Tokyo|Alibaba.com LLC|
|2|47.243.167.134|8889|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|3|51.159.115.233|3128|France|Paris|SCALEWAY|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|213.233.182.39|8000|Iran|Tehran|SHARIF-EDU|
|8|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|9|200.119.89.19|80|Colombia|Bogotá|ETB - Colombia|
|10|23.229.80.169|3129|United States|Buffalo|B2 Net Solutions Inc.|
|11|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|12|23.229.80.183|3129|United States|Buffalo|B2 Net Solutions Inc.|
|13|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|14|103.36.35.135|8080|Indonesia|Kampungbali|PT Mora Telematika Indonesia|
|15|200.106.187.252|999|Argentina|Jose Maria Ezeiza|Fullnet Solutions S.A.S.|
|16|59.25.171.205|3128|South Korea|Jung-gu|Korea Telecom|
|17|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|18|138.121.113.179|8080|Argentina|Formosa|Refsa Telecomunicaciones|
|19|183.172.81.32|7891|China|Haidian|CERNET|
|20|125.75.150.35|9002|China|Yuzhong Chengguanzhen|China Telecom|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


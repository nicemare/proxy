
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6002** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|515|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|515|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|515|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1198|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|689|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2864|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|2|162.223.88.61|8080|United States|Buffalo|ColoUp|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|6|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|7|217.67.190.154|3128|Russia|Moscow|Mastertel ISP|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|10|188.133.153.227|1256|Russia|Moscow|Enforta-MSK|
|11|95.111.239.49|3131|Germany|Nuremberg|Contabo GmbH|
|12|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|13|5.202.103.100|514|Iran|Tehran|Pishgaman Toseeh Ertebatat Company (Private Joint Stock)|
|14|102.130.192.231|8080|Angola|Luanda|Finstar - Sociedade de Investimento e Participacoes S.A|
|15|45.6.4.60|8080|Argentina|San Miguel de Tucumán|Providers S.A.|
|16|200.106.187.247|999|Argentina|Jose Maria Ezeiza|Fullnet Solutions S.A.S.|
|17|5.182.93.169|8080|Russia|Voronezh|Expert PRO LLC|
|18|190.90.39.77|999|Colombia|Arauca|Internexa S.a. E.S.P|
|19|182.253.173.237|8080|Indonesia|Jakarta|Biznet Metronet|
|20|45.156.31.155|9090|Turkey|Istanbul|ATLANTIS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


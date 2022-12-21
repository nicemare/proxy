
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6725** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|641|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|641|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|641|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1559|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|836|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3079|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|172.120.119.209|9527|United States|Santa Clara|EGIHosting|
|2|209.97.152.208|8888|United States|Clifton|DigitalOcean, LLC|
|3|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|4|5.39.105.211|3128|France|Lyon|OVH SAS|
|5|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|6|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|7|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|8|139.99.47.62|3128|Singapore|Singapore|OVH SAS|
|9|143.198.82.124|8081|Singapore|Singapore|DigitalOcean, LLC|
|10|43.231.0.40|7890|Hong Kong|Victoria|BUILDCLOUD|
|11|177.141.99.50|8080|Brazil|São Paulo|Claro NXT Telecomunicacoes Ltda|
|12|179.96.28.58|80|Brazil|Calcilandia|G8 NETWORKS LTDA|
|13|145.40.121.89|3128|Brazil|São Paulo|Packet Host, Inc.|
|14|75.126.253.8|8080|United States|Dallas|SoftLayer|
|15|47.244.2.19|3128|Hong Kong|Central|Alibaba.com LLC|
|16|147.139.191.249|3128|Indonesia|Jakarta|Alibaba.com LLC|
|17|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|18|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|19|179.189.125.222|8080|Brazil|Parnaiba|IP CARRIER BRASIL|
|20|64.227.23.88|8118|United States|North Bergen|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


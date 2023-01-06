
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5443** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|385|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|385|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|385|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1273|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|407|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2712|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.221.104.199|3128|Japan|Tokyo|Google LLC|
|2|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|3|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|4|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|5|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|6|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|47.244.2.19|3128|Hong Kong|Central|Alibaba.com LLC|
|9|45.91.133.137|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|10|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|11|203.115.106.85|8080|India|Greater Noida|PRIMENET|
|12|66.42.53.233|8000|Singapore|Singapore|The Constant Company|
|13|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|14|45.156.29.19|9090|Turkey|Istanbul|Atlantis Telekomunikasyon Bilisim Hizmetleri San. Tic. Ltd|
|15|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|16|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|17|207.5.79.174|3128|United States|Roseville|Network Innovations|
|18|212.46.230.102|6969|Russia|Moscow|PJSC "Vimpelcom"|
|19|201.174.152.190|999|Mexico|Aguascalientes|Transtelco Inc|
|20|159.223.14.199|443|Netherlands|Amsterdam|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


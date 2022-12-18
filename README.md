
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5890** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|353|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|353|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|353|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1207|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|758|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2674|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|2|66.42.53.233|8000|Singapore|Singapore|The Constant Company|
|3|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|4|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|5|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|6|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|165.192.111.151|3129|United States|Seattle|SoftLayer|
|9|45.158.171.3|999|Venezuela|Valencia|NETCOM PLUS, C.A|
|10|47.242.37.241|3128|Hong Kong|Hong Kong|Alibaba.com LLC|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|192.155.95.228|10755|United States|Atlanta|Linode, LLC|
|13|209.146.19.58|55443|Philippines|Manolo Fortich|Cogent Communications|
|14|45.158.171.3|999|Venezuela|Valencia|NETCOM PLUS, C.A|
|15|64.227.6.0|4003|United States|North Bergen|DigitalOcean, LLC|
|16|216.176.187.99|8889|United States|Los Angeles|Wowrack.com|
|17|89.107.197.165|3128|Russia|Tula|LLC TK Altair|
|18|207.180.199.123|443|Germany|Nuremberg|Contabo GmbH|
|19|41.57.50.17|8080|South Africa|eManzimtoti|FTH SCR P8|
|20|51.91.100.252|443|France|Strasbourg|OVH SAS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


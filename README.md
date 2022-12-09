
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5001** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|356|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|356|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|356|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|815|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|464|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2471|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|20.230.175.193|8080|United States|Quincy|Microsoft Corporation|
|4|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|5|64.227.23.88|8118|United States|North Bergen|DigitalOcean, LLC|
|6|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|7|75.126.253.8|8080|United States|Dallas|SoftLayer|
|8|64.227.23.88|8118|United States|North Bergen|DigitalOcean, LLC|
|9|20.230.175.193|8080|United States|Quincy|Microsoft Corporation|
|10|148.251.150.106|3128|Germany|Falkenstein|Hetzner Online GmbH|
|11|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|12|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|13|139.59.228.95|8118|Singapore|Singapore|DIGITALOCEAN|
|14|75.72.55.108|8118|United States|Hopkins|Comcast Cable Communications, LLC|
|15|134.238.252.143|8080|India|Mumbai|Google LLC|
|16|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|17|188.0.147.102|3128|Kazakhstan|Almaty|JSC "KazTransCom"|
|18|223.18.60.191|8080|Hong Kong|Central|HGC Global Communications Limited|
|19|116.202.209.248|8118|Germany|Falkenstein|Hetzner Online GmbH|
|20|131.72.68.107|40033|Brazil|Areia Branca|TOP NET SERVIÇOS LTDA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


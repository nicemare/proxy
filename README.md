
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5488** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|352|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|352|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|352|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1029|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|480|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2728|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|50.114.128.17|3128|Pakistan|Karachi|Delta Centric LLC, Comcast Cable Communications, LLC|
|2|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|134.238.252.143|8080|India|Mumbai|Google LLC|
|6|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|7|51.159.115.233|3128|France|Paris|SCALEWAY|
|8|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|9|184.105.186.70|3128|United States|Omaha|Hurricane Electric LLC|
|10|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|11|45.8.179.242|1337|United Kingdom|London|HOSTLAND|
|12|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|13|102.130.192.231|8080|Angola|Luanda|Finstar - Sociedade de Investimento e Participacoes S.A|
|14|167.114.96.27|9300|Canada|Montreal|OVH SAS|
|15|47.89.250.138|3128|United States|Minkler|Alibaba.com LLC|
|16|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|17|103.180.138.77|10006|Vietnam|Ho Chi Minh City|TANHOANGVINA|
|18|95.17.166.205|8118|Spain|Olot|Orange Spain|
|19|178.210.51.118|8080|Russia|Voronezh|JSC KVANT-TELEKOM|
|20|63.250.52.82|8118|Japan|Tokyo|HIVELOCITY, Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


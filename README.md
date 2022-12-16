
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5248** proxies at the latest update. Usable proxies are below.

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
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|910|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|642|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2745|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|135.148.95.28|3128|United States|Reston|OVH SAS|
|3|54.196.147.230|8080|United States|Ashburn|Amazon.com, Inc.|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|135.148.95.28|3128|United States|Reston|OVH SAS|
|6|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|7|192.155.95.228|10801|United States|Atlanta|Linode, LLC|
|8|192.155.95.228|10801|United States|Atlanta|Linode, LLC|
|9|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|10|43.231.0.40|7890|Hong Kong|Victoria|BUILDCLOUD|
|11|165.192.111.151|3129|United States|Seattle|SoftLayer|
|12|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|13|134.238.252.143|8080|India|Mumbai|Google LLC|
|14|54.151.6.61|3128|United States|San Jose|Amazon.com, Inc.|
|15|164.92.73.145|3128|United States|Santa Clara|DigitalOcean, LLC|
|16|70.177.15.10|8080|United States|Gilbert|Cox Communications Inc.|
|17|181.78.104.201|999|Guatemala|Guatemala City|Ufinet Panama S.A.|
|18|187.216.93.20|55443|Mexico|Mexico City|Uninet S.A. de C.V.|
|19|177.22.88.224|3128|Brazil|Passo Fundo|Coprel Telecom Ltda|
|20|45.234.60.50|999|Venezuela|San Antonio de Los Altos|SOLUCIONES INSTALRED CH&C C.A.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


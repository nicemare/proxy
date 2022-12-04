
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4189** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|126|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|126|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|126|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|436|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|149|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2253|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.13|3128|United States|Ashburn|Bernardi Sounds|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|208.82.61.12|3128|United States|Ashburn|Bernardi Sounds|
|4|45.152.188.16|3128|United States|Ashburn|Sprint|
|5|208.82.61.13|3128|United States|Ashburn|Bernardi Sounds|
|6|45.152.188.16|3128|United States|Ashburn|Sprint|
|7|208.82.61.12|3128|United States|Ashburn|Bernardi Sounds|
|8|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|89.250.152.76|8080|Russia|Tyumen|JSC "ER-Telecom Holding"|
|11|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|12|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|13|208.82.61.12|3128|United States|Ashburn|Bernardi Sounds|
|14|45.167.125.97|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|15|172.105.226.115|443|Japan|Tokyo|Linode, LLC|
|16|116.106.200.60|4001|Vietnam|Ho Chi Minh City|Viettel Corporation|
|17|171.103.58.122|8080|Thailand|Bangkok|True Internet Co., Ltd.|
|18|27.79.183.246|4001|Vietnam|Hanoi|Viettel Corporation|
|19|24.160.184.10|9999|United States|Solon|Charter Communications|
|20|75.126.253.8|8080|United States|Dallas|SoftLayer|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


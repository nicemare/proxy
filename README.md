
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5208** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|480|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|480|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|480|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|911|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|440|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2606|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|103.114.162.212|31181|United States|Las Vegas|DediPath|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|45.152.188.248|3128|United States|Ashburn|Sprint|
|4|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|5|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|6|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|7|75.126.253.8|8080|United States|Dallas|SoftLayer|
|8|179.96.28.58|80|Brazil|São Paulo|G8 NETWORKS LTDA|
|9|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|10|103.114.162.212|31181|United States|Las Vegas|DediPath|
|11|45.152.188.248|3128|United States|Ashburn|Sprint|
|12|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|13|119.76.142.208|8080|Thailand|Nakhon Ratchasima|True Internet Co., Ltd.|
|14|203.32.21.250|3128|Turkey|Bursa|DGN TEKNOLOJI A.S.|
|15|158.69.71.245|9300|Canada|Montreal|OVH SAS|
|16|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|17|87.247.186.105|80|Iran|Tehran|Insightometrics B.V.|
|18|161.35.223.141|80|Germany|Frankfurt am Main|DigitalOcean, LLC|
|19|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|20|63.250.53.181|3128|United Kingdom|London|HIVELOCITY, Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


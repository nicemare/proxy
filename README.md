
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4252** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|204|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|204|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|204|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|428|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|154|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2319|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|2|93.104.210.181|3128|Germany|Munich|MNET|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|45.167.126.78|3128|Colombia|Popayán|Sepcom Comunicaciones SAS|
|5|212.46.210.235|8080|Russia|Moscow|VympelKom broadband internet|
|6|188.166.210.198|8123|Singapore|Singapore|DigitalOcean, LLC|
|7|112.137.142.8|3128|Vietnam|Hanoi|VietNam National University|
|8|117.251.103.186|8080|India|Noida|BSNL Internet|
|9|46.209.207.148|8080|Iran|Tehran|Respina|
|10|103.101.229.15|8080|Indonesia|Bendungan Hilir|Biznet Networks|
|11|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|12|103.252.1.137|3128|Vietnam|Hanoi|CMCMIENBAC|
|13|110.136.30.49|8080|Indonesia|Blitar|PT. TELKOM INDONESIA|
|14|182.253.109.83|8080|Indonesia|Semarang|Biznet Metronet|
|15|112.140.186.124|808|Singapore|Singapore|Sparkstation Pte Ltd|
|16|36.90.12.199|80|Indonesia|Jakarta|PT. Telekomunikasi Indonesia|
|17|134.238.252.143|8080|India|Mumbai|Google LLC|
|18|60.51.88.126|8080|Malaysia|Shah Alam|Tmnet, Telekom Malaysia Bhd.|
|19|176.126.83.189|3128|Italy|Milan|Seflow S.N.C. Di Marco Brame' & C.|
|20|122.49.208.242|3128|Philippines|San Juan|WifiCity, Inc|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


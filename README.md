
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5340** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|401|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|401|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|401|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|878|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|720|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2491|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|192.155.95.228|10801|United States|Atlanta|Linode, LLC|
|4|190.45.251.189|3128|Chile|Santiago|VTR BANDA ANCHA S.A.|
|5|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|6|202.181.14.23|3128|Bangladesh|Dhaka|BDPEER|
|7|145.40.121.15|3128|Brazil|São Paulo|Packet Host, Inc.|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|209.146.19.58|55443|Philippines|Manolo Fortich|Cogent Communications|
|10|105.174.7.254|8080|Angola|Luanda|UNITEL SA|
|11|188.132.222.37|8080|Turkey|Orhanlı|High Speed Telekomunikasyon ve Hab. Hiz. Ltd. Sti.|
|12|190.63.35.30|9812|Ecuador|Ambato|CONECEL|
|13|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|14|159.89.128.130|8989|United States|Santa Clara|DigitalOcean, LLC|
|15|172.120.119.209|9527|United States|Santa Clara|EGIHosting|
|16|202.40.188.92|40486|Bangladesh|Dhaka|Ranks ITT|
|17|45.234.60.50|999|Venezuela|San Antonio de Los Altos|SOLUCIONES INSTALRED CH&C C.A.|
|18|204.199.131.198|999|Chile|Santiago|Level 3 Communications, Inc.|
|19|168.228.168.221|80|Brazil|Bodoquena|Ivr informatica ltda me|
|20|50.236.203.15|8080|United States|Oak Park|Comcast Cable Communications, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


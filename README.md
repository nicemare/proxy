
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5400** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|415|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|415|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|415|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|939|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|541|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2669|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|51.159.115.233|3128|France|Paris|SCALEWAY|
|3|45.167.125.61|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|4|190.45.251.189|3128|Chile|Santiago|VTR BANDA ANCHA S.A.|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|7|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|8|192.155.95.228|10801|United States|Atlanta|Linode, LLC|
|9|105.174.7.254|8080|Angola|Luanda|UNITEL SA|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|12|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|13|45.234.60.50|999|Venezuela|San Antonio de Los Altos|SOLUCIONES INSTALRED CH&C C.A.|
|14|40.85.152.26|8080|United States|San Francisco|Microsoft Corporation|
|15|3.16.39.15|3128|United States|Dublin|Amazon.com, Inc.|
|16|154.16.180.182|3128|United States|Dulles|LYIT Internet Services|
|17|212.3.135.57|8080|Russia|Smolensk|Smolensk branch of the JSC "CenterTelecom"|
|18|189.126.106.31|3129|Brazil|Itacoatiara|Locaweb Serviços de Internet S/A|
|19|216.176.187.99|8889|United States|Los Angeles|Wowrack.com|
|20|38.49.135.249|999|Mexico|Querétaro City|Ientc S De RL De CV|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


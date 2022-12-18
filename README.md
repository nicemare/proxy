
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5440** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|455|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|455|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|455|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|979|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|541|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2669|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|3|45.167.125.61|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|4|82.65.249.238|8080|France|Paris|Proxad / Free SAS|
|5|149.154.157.17|5678|Italy|Milan|EDIS|
|6|75.126.253.8|8080|United States|Dallas|SoftLayer|
|7|190.45.251.189|3128|Chile|Santiago|VTR BANDA ANCHA S.A.|
|8|66.42.53.233|8000|Singapore|Singapore|The Constant Company|
|9|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|10|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|11|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|12|40.85.152.26|8080|United States|San Francisco|Microsoft Corporation|
|13|134.238.252.143|8080|India|Mumbai|Google LLC|
|14|184.105.182.254|3128|United States|Gilroy|Hurricane Electric LLC|
|15|47.252.4.64|8888|United States|Charlottesville|Alibaba.com LLC|
|16|154.16.180.182|3128|United States|Dulles|LYIT Internet Services|
|17|189.126.106.31|3129|Brazil|Itacoatiara|Locaweb Serviços de Internet S/A|
|18|38.49.135.249|999|Mexico|Querétaro City|Ientc S De RL De CV|
|19|185.200.36.165|8888|Turkey|Antakya|High Speed Telekomunikasyon ve Hab. Hiz. Ltd. Sti.|
|20|105.174.7.254|8080|Angola|Luanda|UNITEL SA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


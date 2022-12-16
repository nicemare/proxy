
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5460** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|316|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|316|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|316|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1020|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|433|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2756|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|185.81.98.16|3131|Netherlands|Naaldwijk|WorldStream B.V.|
|3|37.112.57.47|8080|Russia|Bryansk|CJSC "ER-Telecom Holding" Bryansk branch|
|4|135.148.95.28|3128|United States|Reston|OVH SAS|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|135.148.95.28|3128|United States|Reston|OVH SAS|
|7|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|8|54.151.6.61|3128|United States|San Jose|Amazon.com, Inc.|
|9|158.255.212.55|3256|Austria|Vienna|EDIS GmbH|
|10|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|11|134.238.252.143|8080|India|Mumbai|Google LLC|
|12|188.0.147.102|3128|Kazakhstan|Almaty|JSC "KazTransCom"|
|13|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|14|116.0.61.122|3128|Pakistan|Karachi|Telecard|
|15|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|16|172.105.226.115|443|Japan|Tokyo|Linode, LLC|
|17|93.115.146.48|8080|Iran|Tehran|Asiatech Data Transmission company|
|18|51.159.115.233|3128|France|Paris|SCALEWAY|
|19|5.160.179.8|8080|Iran|Tehran|Respina Networks & Beyond PJSC|
|20|179.60.235.250|8096|Argentina|Rosario|WICORP SA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


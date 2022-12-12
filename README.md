
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5006** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|302|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|302|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|302|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|831|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|357|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2567|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|2|157.230.209.225|3128|United States|North Bergen|DigitalOcean, LLC|
|3|142.129.238.249|80|United States|Pomona|Charter Communications Inc|
|4|109.238.14.216|3128|France|Boulogne-Billancourt|Ikoula Net SAS|
|5|157.230.209.225|3128|United States|North Bergen|DigitalOcean, LLC|
|6|185.81.98.17|3131|Netherlands|Naaldwijk|WorldStream B.V.|
|7|52.45.139.115|80|United States|Ashburn|Amazon.com, Inc.|
|8|172.81.60.161|3128|United States|Phoenix|Dynu Systems Incorporated|
|9|157.100.55.143|999|Ecuador|Guayaquil|Nedetel S.A.|
|10|158.69.71.245|9300|Canada|Montreal|OVH SAS|
|11|47.74.226.8|5001|Singapore|Singapore|Alibaba Cloud (Singapore) Private Limited|
|12|87.247.186.105|80|Iran|Tehran|Insightometrics B.V.|
|13|45.152.188.248|3128|United States|Ashburn|Sprint|
|14|154.85.55.174|3128|United States|Los Angeles|Beijing Baidu Netcom Science and Technology Co., Ltd.|
|15|47.57.233.110|808|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|16|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|17|143.244.133.78|80|India|Bengaluru|DigitalOcean, LLC|
|18|45.152.188.248|3128|United States|Ashburn|Sprint|
|19|5.58.110.249|8080|Ukraine|Ternopil|Columbus|
|20|121.54.190.92|3129|United States|Los Angeles|Zenlayer Inc|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6135** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|541|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|541|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|541|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1261|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|637|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2986|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|2|51.159.115.233|3128|France|Paris|SCALEWAY|
|3|81.4.102.233|8081|Netherlands|Amsterdam|WeservIT|
|4|81.4.102.223|8081|Netherlands|Amsterdam|WeservIT|
|5|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|8|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|9|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|10|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|11|159.192.253.165|8080|Thailand|Bangkok|CAT-BB|
|12|111.68.24.113|3127|Indonesia|Yogyakarta|GMEDIA|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|200.8.190.45|999|Venezuela|Barquisimeto|Corporación Telemic C.A.|
|15|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|16|62.32.92.124|8080|Kazakhstan|Almaty|Obit Telecommunications|
|17|188.72.6.98|37083|Iraq|Sulaymaniyah|AL-SARD FIBER Co. for Internet Fiber and Optical Cable Services /Ltd.|
|18|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|19|185.120.162.28|443|Iran|Tehran|Khallagh Borhan Market Development for Creative Industries Co|
|20|196.250.239.229|8787|South Africa|Cape Town|West Indian Ocean Cable Company|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


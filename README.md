
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5243** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|367|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|367|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|367|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|834|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|536|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2622|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|209.141.54.136|5555|United States|Las Vegas|FranTech Solutions|
|2|52.155.227.108|3128|Ireland|Dublin|Microsoft Corporation|
|3|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|4|209.141.54.136|5555|United States|Las Vegas|FranTech Solutions|
|5|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|6|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|185.81.98.17|3131|Netherlands|Naaldwijk|WorldStream B.V.|
|9|159.192.249.10|8080|Thailand|Bangkok|CAT-BB|
|10|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|11|176.196.250.86|3128|Russia|Kemerovo|Goodline.info|
|12|52.87.136.220|80|United States|Ashburn|Amazon.com, Inc.|
|13|45.152.188.248|3128|United States|Ashburn|Sprint|
|14|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|15|36.90.90.223|8080|Indonesia|Karangampel|PT. Telekomunikasi Indonesia|
|16|103.147.246.84|8080|Indonesia|Jakarta|PLBNET|
|17|45.174.168.2|999|Mexico|Tulancingo|Wiiki Networks S De R.l. De C.V.|
|18|172.81.60.161|3128|United States|Phoenix|Dynu Systems Incorporated|
|19|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|20|88.255.101.228|8080|Turkey|Antalya|Turk Telekomunikasyon Anonim Sirketi|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


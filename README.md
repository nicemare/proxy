
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4526** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|254|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|254|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|254|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|507|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|465|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2303|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|2|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|3|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|4|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|5|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|6|134.122.85.174|8888|Germany|Frankfurt am Main|DigitalOcean, LLC|
|7|194.195.90.215|8118|Singapore|Singapore|Contabo Asia Private Limited|
|8|172.104.128.235|8888|Germany|Frankfurt am Main|Linode, LLC|
|9|103.231.241.102|80|Philippines|Quezon City|De La Salle University|
|10|201.73.228.20|3128|Brazil|Rio de Janeiro|Claro S.A|
|11|45.152.188.248|3128|United States|Ashburn|Sprint|
|12|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|13|134.238.252.143|8080|India|Mumbai|Google LLC|
|14|141.8.193.104|8118|Russia|Untolovo|Sprinthost P17|
|15|36.80.140.93|8080|Indonesia|Semarang|PT. TELKOM INDONESIA|
|16|45.152.188.248|3128|United States|Ashburn|Sprint|
|17|37.112.29.117|55443|Russia|Penza|JSC "ER-Telecom Holding"|
|18|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|19|176.56.107.232|35186|Spain|Cehegín|Aire Networks|
|20|103.160.15.38|3125|Indonesia|Tanjung Pinang|PT INFORMASI NUSANTARA TEKNOLOGI|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


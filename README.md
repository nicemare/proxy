
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6024** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|223|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|223|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|223|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1313|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|611|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2749|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|34.66.5.144|8888|United States|Council Bluffs|Google LLC|
|2|192.210.196.65|9090|United States|Chicago|ColoCrossing|
|3|103.200.112.112|8123|Hong Kong|Tseung Kwan O|Shanghai Huajuan Information Technology Co., Ltd.|
|4|20.121.184.238|9401|United States|Boydton|Microsoft Corporation|
|5|163.123.183.222|10000|United States|League City|WholeSale Internet, Inc.|
|6|187.17.228.98|3128|Brazil|Louveira|Lantec Comunicacao Multimidia Ltda|
|7|88.99.215.253|808|Germany|Falkenstein|Hetzner Online GmbH|
|8|143.198.56.234|443|United States|Santa Clara|DigitalOcean, LLC|
|9|45.233.67.225|999|Guatemala|Jalapa|Conectividad Y Tecnologia S.A|
|10|112.87.140.164|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|11|145.40.121.73|3128|Brazil|São Paulo|Packet Host, Inc.|
|12|186.227.49.186|3128|Brazil|Rio de Janeiro|Voipglobe Servicos De COM Multimidia VIA Internet|
|13|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|14|20.121.184.238|9401|United States|Boydton|Microsoft Corporation|
|15|51.255.99.186|3128|France|Cannes|OVH SAS|
|16|45.156.31.187|9090|Turkey|Istanbul|ATLANTIS|
|17|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|18|68.178.202.127|3128|United States|Tempe|GoDaddy.com, LLC|
|19|110.164.162.45|80|Thailand|Bangkok|Triple T Internet Company Limited|
|20|103.172.179.228|83|India|Hyderabad|CtrlS Datacenters Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


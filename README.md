
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4715** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|208|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|208|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|208|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|588|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|252|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2624|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|4|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|5|191.252.195.53|8888|Brazil|Itacoatiara|Locaweb Serviços de Internet S/A|
|6|5.196.124.204|80|France|Roubaix|OVH SAS|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|9|103.180.139.111|10003|Vietnam|Ho Chi Minh City|TANHOANGVINA|
|10|192.155.95.228|10000|United States|Atlanta|Linode, LLC|
|11|64.227.23.88|8118|United States|North Bergen|DigitalOcean, LLC|
|12|45.91.81.132|1080|United States|Los Angeles|FD-298-8796|
|13|177.93.50.234|999|Colombia|San José del Guaviare|TV AZTECA SUCURSAL COLOMBIA|
|14|158.69.53.98|9300|Canada|Montreal|OVH SAS|
|15|116.58.232.155|8080|Thailand|Nong Khaem|CAT-BB|
|16|171.103.58.122|8080|Thailand|Bangkok|True Internet Co., Ltd.|
|17|163.172.85.160|9741|France|Paris|Online S.A.S.|
|18|103.178.231.186|10003|Vietnam|Da Nang|DATHANH|
|19|122.155.165.191|3128|Thailand|Ratchathewi|CAT Telecom Public Company Limited|
|20|5.58.110.249|8080|Ukraine|Ternopil|Columbus|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


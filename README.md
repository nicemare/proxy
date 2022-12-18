
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5280** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|414|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|414|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|414|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1093|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|550|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2386|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|47.242.37.241|3128|Hong Kong|Hong Kong|Alibaba.com LLC|
|6|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|7|91.92.122.215|8080|Iran|Tehran|TIC|
|8|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|9|180.183.122.106|8080|Thailand|Bangkok|Triple T Broadband Public Company Limited|
|10|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|11|41.216.155.245|8080|Burkina Faso|Saaba|connecteo-burkina|
|12|192.155.95.228|10755|United States|Atlanta|Linode, LLC|
|13|188.246.163.163|41258|Russia|Moscow|OOO WestCall Ltd|
|14|103.147.246.129|8080|Indonesia|Serang|PLBNET|
|15|116.107.50.250|4005|Vietnam|Phu Ly|Viettel Corporation|
|16|217.66.200.154|3128|Iran|Tehran|Tose'h Fanavari Ertebabat Pasargad Arian Co. PJS|
|17|209.146.19.58|55443|Philippines|Manolo Fortich|Cogent Communications|
|18|118.172.187.127|8080|Thailand|Khwaeng Thung Song Hong|TOT Public Company Limited|
|19|109.224.51.30|8080|Iraq|Baghdad|EarthLink Ltd. Communications&Internet Services|
|20|103.229.185.22|80|Indonesia|Pamulang|PT INDONESIA COMNETS PLUS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


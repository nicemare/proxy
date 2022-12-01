
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4618** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|204|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|204|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|204|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|584|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|214|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2469|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|5|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|6|38.117.65.149|8080|Canada|Toronto|Ravand Cybertech Inc.|
|7|52.87.136.220|80|United States|Ashburn|Amazon.com, Inc.|
|8|75.126.253.8|8080|United States|Dallas|SoftLayer|
|9|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|49.51.90.57|3128|Canada|Barrie|OPHL|
|12|38.117.65.149|8080|Canada|Toronto|Ravand Cybertech Inc.|
|13|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|14|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|15|52.87.136.220|80|United States|Ashburn|Amazon.com, Inc.|
|16|103.168.129.123|8080|Indonesia|Jakarta|LINTASARTA|
|17|190.216.107.194|999|Ecuador|Quito|Level 3 ECUADOR LVLT S.A|
|18|190.216.107.196|999|Ecuador|Quito|Level 3 ECUADOR LVLT S.A|
|19|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|20|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


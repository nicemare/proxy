
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5910** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|401|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|401|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|401|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1340|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|816|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2803|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|45.152.188.248|3128|United States|Ashburn|Sprint|
|3|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|4|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|5|135.148.95.28|3128|United States|Reston|OVH SAS|
|6|181.205.116.218|9812|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|7|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|8|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|9|8.210.222.224|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|10|192.155.95.228|10000|United States|Atlanta|Linode, LLC|
|11|91.108.134.84|8080|Iran|Behbahan|Fara Negar|
|12|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|13|212.115.232.79|31280|Ukraine|Dnipro|ISP "Fregat"|
|14|38.54.85.165|7890|Hong Kong|Hong Kong|Kaopu Cloud HK Limited|
|15|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|16|75.126.253.8|8080|United States|Dallas|SoftLayer|
|17|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|18|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|19|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|20|24.172.82.94|53281|United States|Huntersville|Spectrum|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


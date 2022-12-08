
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4944** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|255|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|255|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|255|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|788|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|428|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2445|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|51.222.75.219|8080|Canada|Beauharnois|OVH Hosting|
|3|45.152.188.16|3128|United States|Ashburn|Sprint|
|4|45.152.188.16|3128|United States|Ashburn|Sprint|
|5|134.238.252.143|8080|India|Mumbai|Google LLC|
|6|119.42.115.27|8080|Thailand|Bangkok|CAT-BB|
|7|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|8|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|9|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|10|75.126.253.8|8080|United States|Dallas|SoftLayer|
|11|75.126.253.8|8080|United States|Dallas|SoftLayer|
|12|116.80.41.12|80|Japan|Chiyoda|InfoSphere|
|13|122.155.165.191|3128|Thailand|Ratchathewi|CAT Telecom Public Company Limited|
|14|5.44.54.16|8080|Russia|Perm|JSC "ER-Telecom Holding"|
|15|91.90.180.185|8080|Poland|Krakow|3S S.A. LIR|
|16|181.205.106.106|9812|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|17|190.61.60.118|999|Panama|Panama City|Ufinet Panama S.A|
|18|190.202.94.210|8080|Venezuela|Santa Rita|CANTV Servicios, Venezuela|
|19|185.142.43.217|8080|Lebanon|Bednâyel|Net Pro sarl|
|20|45.152.188.248|3128|United States|Ashburn|Sprint|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


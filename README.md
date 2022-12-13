
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4511** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|246|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|246|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|246|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|0|🚫|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|597|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|350|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2328|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|8.29.103.131|8080|United States|Dawsonville|North Georgia Network Cooperative, Inc|
|3|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|4|51.79.152.70|3128|Singapore|Singapore|OVH SAS|
|5|45.152.188.248|3128|United States|Ashburn|Sprint|
|6|154.16.180.182|3128|United States|Dulles|LYIT Internet Services|
|7|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|8|181.129.14.164|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|11|145.40.121.165|3128|Brazil|São Paulo|Packet Host, Inc.|
|12|145.40.121.163|3128|Brazil|São Paulo|Packet Host, Inc.|
|13|75.126.253.8|8080|United States|Dallas|SoftLayer|
|14|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|15|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|16|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|17|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|18|103.77.76.54|8080|Indonesia|Kota Matsum Tiga|Rackh Lintas Asia|
|19|45.152.188.248|3128|United States|Ashburn|Sprint|
|20|154.19.187.251|3128|Japan|Tokyo|SICLOUD INFORMATION TECHNOLOGY (HONGKONG) CO., LIMITED|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


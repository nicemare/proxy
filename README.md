
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5078** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|351|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|351|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|351|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|935|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|390|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2402|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|49.51.90.57|3128|Canada|Barrie|OPHL|
|4|52.87.136.220|80|United States|Ashburn|Amazon.com, Inc.|
|5|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|6|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|7|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|8|86.120.122.3|3128|Romania|Pipera|RCS & RDS|
|9|85.14.243.31|3128|Germany|Kamp-Lintfort|myLoc managed IT AG|
|10|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|11|75.126.253.8|8080|United States|Dallas|SoftLayer|
|12|144.76.119.59|1988|Germany|Falkenstein|Hetzner Online GmbH|
|13|134.238.252.143|8080|India|Mumbai|Google LLC|
|14|148.251.184.47|1988|Germany|Falkenstein|Hetzner Online GmbH|
|15|161.53.129.23|3128|Croatia|Krapinske Toplice|Croatian Academic and Research Network|
|16|51.159.115.233|3128|France|Paris|SCALEWAY|
|17|157.100.12.138|999|Ecuador|Loja|Telconet S.A|
|18|201.222.45.60|999|Chile|Santiago|GRUPO ULLOA SpA|
|19|103.164.151.51|3125|Indonesia|Pekanbaru|PT. Aditama Netmedia Solusindo|
|20|195.225.232.3|8085|Iran|Tehran|TS Information Technology Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


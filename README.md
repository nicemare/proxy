
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5003** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|365|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|365|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|365|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|769|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|374|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2577|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|2|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|3|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|4|160.19.95.121|1337|Spain|Madrid|Stallion Network Services Limited|
|5|92.119.34.121|1337|Netherlands|Amsterdam|NovoServe B.V.|
|6|185.104.112.148|3128|Poland|Ełk|Timeweb-Artnet|
|7|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|8|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|9|160.16.62.193|3190|Japan|Tokyo|SAKURA Internet Inc.|
|10|143.198.86.67|8080|Singapore|Singapore|DigitalOcean, LLC|
|11|134.238.252.143|8080|India|Mumbai|Google LLC|
|12|117.251.103.186|8080|India|Noida|BSNL Internet|
|13|122.49.208.242|3128|Philippines|San Juan|WifiCity, Inc|
|14|189.164.76.71|10101|Mexico|Puebla City|Uninet S.A. de C.V|
|15|155.4.244.218|80|Sweden|Stockholm|Bahnhof AB|
|16|160.16.120.80|3190|Japan|Tokyo|SAKURA Internet Inc.|
|17|94.103.85.88|9300|Russia|Moscow|VDSINA|
|18|172.105.216.60|443|Japan|Tokyo|Linode, LLC|
|19|160.16.149.247|3190|Japan|Tokyo|SAKURA Internet Inc.|
|20|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


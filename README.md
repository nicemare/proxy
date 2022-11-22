
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4605** proxies at the latest update. Usable proxies are below.

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
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|583|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|318|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2353|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.42.177.50|3128|United States|Ashburn|Sprint|
|2|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|3|45.42.177.50|3128|United States|Ashburn|Sprint|
|4|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|5|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|8|117.251.103.186|8080|India|Noida|BSNL Internet|
|9|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|10|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|11|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|12|122.49.208.230|3128|Philippines|San Juan|WifiCity, Inc|
|13|174.138.116.12|80|United States|Clifton|DigitalOcean, LLC|
|14|75.126.253.8|8080|United States|Dallas|SoftLayer|
|15|87.101.4.225|80|Netherlands|Herkenbosch|Cambrium IT Services B.V.|
|16|195.225.232.3|8085|Iran|Tehran|TS Information Technology Limited|
|17|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|18|190.15.151.241|999|Cuba|Havana|Empresa de Telecomunicaciones de Cuba, S.A.|
|19|220.241.131.164|3128|Hong Kong|Central|PCCW IMS Ltd (PCCW Business Internet Access)|
|20|195.39.233.18|8080|Ukraine|Kharkiv|Active Operations LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


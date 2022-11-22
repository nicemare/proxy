
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4608** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|235|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|235|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|235|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|717|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|215|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2325|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|167.71.190.253|80|United States|Clifton|DigitalOcean, LLC|
|3|167.71.190.253|80|United States|Clifton|DigitalOcean, LLC|
|4|195.178.197.20|8080|Russia|Podolsk|IIP|
|5|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|8|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|9|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|10|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|11|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|12|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|13|176.56.107.99|51528|Spain|Cehegín|Aire Networks|
|14|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|
|15|122.49.208.242|3128|Philippines|San Juan|WifiCity, Inc|
|16|190.63.35.30|9812|Ecuador|Ambato|CONECEL|
|17|85.14.243.31|3128|Germany|Kamp-Lintfort|myLoc managed IT AG|
|18|75.111.123.158|1888|United States|Clovis|Suddenlink Communications|
|19|87.247.186.105|80|Iran|Tehran|Insightometrics B.V.|
|20|91.211.245.202|3128|Lithuania|Vilnius|UAB ESNET|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


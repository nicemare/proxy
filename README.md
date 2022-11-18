
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5086** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|385|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|385|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|385|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|776|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|567|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2460|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|20.234.198.245|8080|Netherlands|Amsterdam|Microsoft Corporation|
|2|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|3|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|4|192.162.239.137|8080|Ukraine|Vinnytsia|VINASTERISK, PP|
|5|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|6|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|7|181.215.178.39|1337|Netherlands|Amsterdam|NovoServe B.V.|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|20.229.33.75|8080|Netherlands|Amsterdam|Microsoft Corporation|
|10|117.251.103.186|8080|India|Noida|BSNL Internet|
|11|188.121.120.185|80|Iran|Tehran|Noyan Abr Arvan Co. ( Private Joint Stock)|
|12|178.35.152.62|8080|Russia|Volgograd|Volgograd Electro Svyaz|
|13|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|
|14|51.159.115.233|3128|France|Paris|SCALEWAY|
|15|54.88.125.126|9999|United States|Ashburn|Amazon.com, Inc.|
|16|20.113.40.250|3128|Germany|Frankfurt am Main|Microsoft Corporation|
|17|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|18|27.79.33.95|10000|Vietnam|Buon Ma Thuot|Viettel Corporation|
|19|190.63.35.30|9812|Ecuador|Ambato|CONECEL|
|20|118.89.176.33|8118|China|Shenzhen|Shenzhen Tencent Computer Systems Company Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4350** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|216|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|216|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|216|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|408|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|279|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2280|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|54.37.242.66|3128|United Kingdom|London|OVH SAS|
|2|134.122.50.151|3128|Netherlands|Amsterdam|DigitalOcean, LLC|
|3|95.211.156.132|3128|Netherlands|Haarlem|LeaseWeb Netherlands B.V.|
|4|20.113.40.250|3128|Germany|Frankfurt am Main|Microsoft Corporation|
|5|51.159.115.233|3128|France|Paris|SCALEWAY|
|6|194.26.232.30|3128|Netherlands|Amsterdam|Zomro B.V.|
|7|51.158.153.158|2019|France|Paris|SCALEWAY|
|8|157.245.76.5|3128|Netherlands|Amsterdam|DigitalOcean, LLC|
|9|45.9.188.100|8888|Netherlands|Meppel|Hostinger International Limited|
|10|176.126.83.189|3128|Italy|Milan|Seflow S.N.C. Di Marco Brame' & C.|
|11|134.122.85.174|8888|Germany|Frankfurt am Main|DigitalOcean, LLC|
|12|175.196.107.133|3128|South Korea|Seoul|Korea Telecom|
|13|20.187.72.38|3128|Hong Kong|Hong Kong|Microsoft Corporation|
|14|220.241.131.164|3128|Hong Kong|Central|Hong Kong Telecommunications (HKT) Limited Business Internet|
|15|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|16|117.251.103.186|8080|India|Hazratpur|BSNL Internet|
|17|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|18|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|19|181.78.104.183|999|Guatemala|Guatemala City|Ufinet Panama S.A.|
|20|191.97.19.57|999|Venezuela|Caracas|INVERSIONES FRITZ 78 C.A.(WIFI SOLUTION)|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


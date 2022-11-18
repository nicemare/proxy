
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5000** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|464|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|464|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|464|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|932|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|362|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2423|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|2|45.167.126.78|3128|Colombia|Popayán|Sepcom Comunicaciones SAS|
|3|165.192.111.151|3129|United States|Dallas|SoftLayer|
|4|160.19.95.121|1337|Spain|Madrid|Stallion Network Services Limited|
|5|92.119.34.121|1337|Netherlands|Amsterdam|NovoServe B.V.|
|6|201.229.250.22|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|7|160.16.63.39|3190|Japan|Tokyo|SAKURA Internet Inc.|
|8|145.40.121.157|3128|Brazil|São Paulo|Packet Host, Inc.|
|9|52.67.176.72|8888|Brazil|São Paulo|Amazon Technologies Inc.|
|10|160.16.141.82|3190|Japan|Tokyo|SAKURA Internet Inc.|
|11|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|12|206.62.161.7|999|Colombia|Maicao|Airtek Solutions C.A.|
|13|165.192.111.151|3129|United States|Dallas|SoftLayer|
|14|172.104.60.117|3128|Singapore|Singapore|Linode, LLC|
|15|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|16|134.238.252.143|8080|India|Mumbai|Google LLC|
|17|27.79.2.54|10000|Vietnam|Hanoi|Viettel Corporation|
|18|27.79.41.123|10000|Vietnam|Hanoi|Viettel Corporation|
|19|117.251.103.186|8080|India|Hazratpur|BSNL Internet|
|20|118.99.73.45|8080|Indonesia|Jakarta|BIZNET|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4545** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|230|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|230|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|230|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|580|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|361|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2353|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.42.177.50|3128|United States|Ashburn|Sprint|
|2|107.152.42.141|8080|United States|Chicago|tzulo, inc.|
|3|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|4|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|5|135.181.22.40|3128|Finland|Helsinki|Hetzner Online GmbH|
|6|45.42.177.50|3128|United States|Ashburn|Sprint|
|7|45.167.126.78|3128|Colombia|Popayán|Sepcom Comunicaciones SAS|
|8|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|9|107.152.42.141|8080|United States|Chicago|tzulo, inc.|
|10|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|11|178.238.236.233|3128|Germany|Munich|Contabo GmbH|
|12|134.238.252.143|8080|India|Mumbai|Google LLC|
|13|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|14|182.253.109.234|8080|Indonesia|Semarang|Biznet Metronet|
|15|201.229.250.22|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|16|193.164.133.46|3128|Germany|Munich|Contabo GmbH|
|17|195.225.232.3|8085|Iran|Tehran|TS Information Technology Limited|
|18|93.175.204.173|8080|Ukraine|Ivano-Frankivsk|Teleradiocompany Discovery Ltd|
|19|89.107.197.165|3128|Russia|Tula|LLC TK Altair|
|20|122.49.208.230|3128|Philippines|San Juan|WifiCity, Inc|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


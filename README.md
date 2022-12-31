
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6307** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|363|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|363|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|363|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1347|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|777|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2832|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|142.4.215.171|3128|Canada|Beauharnois|OVH SAS|
|2|34.84.72.91|3128|Japan|Tokyo|Google LLC|
|3|157.230.241.229|443|Singapore|Singapore|DigitalOcean, LLC|
|4|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|
|5|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|188.166.95.244|443|Netherlands|Amsterdam|DigitalOcean, LLC|
|8|103.242.119.88|80|India|Kolkata|Web Werks India Pvt. Ltd.|
|9|66.79.122.16|8080|Iran|Tehran|Iran Telecommunication Company PJS|
|10|200.25.254.193|54240|Colombia|Bogotá|Andinet ON Line|
|11|54.162.153.60|3128|United States|Ashburn|Amazon.com, Inc.|
|12|116.98.53.240|4012|Vietnam|Da Nang|Viettel Corporation|
|13|116.98.53.240|4012|Vietnam|Da Nang|Viettel Corporation|
|14|103.189.222.5|8080|Indonesia|Tangerang|PT. WIKAPLUS GLOBAL NUSANTARA|
|15|181.129.49.214|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|16|191.102.64.146|999|Colombia|Manizales|TV AZTECA SUCURSAL COLOMBIA|
|17|50.232.250.157|8080|United States|Ferndale|Comcast Cable Communications, LLC|
|18|129.150.42.42|3128|Singapore|Singapore|Oracle Corporation|
|19|128.69.178.155|8080|Russia|Cherepovets|CORBINA-BROADBAND|
|20|185.108.140.69|8080|Bulgaria|Beden|NetX|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


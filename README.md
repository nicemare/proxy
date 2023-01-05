
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5603** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|318|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|318|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|318|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1122|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|587|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2543|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|2|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|3|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|4|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|5|207.5.79.174|3128|United States|Roseville|Network Innovations|
|6|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|7|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|8|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|212.14.243.29|8080|Palestine|Nablus|PALTEL (Palestine Telecommunications Co.).|
|11|45.91.133.137|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|12|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|13|103.242.119.88|80|India|Kolkata|Web Werks India Pvt. Ltd.|
|14|89.132.144.41|9090|Hungary|Budapest|Vodafone Hungary Ltd.|
|15|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|16|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|17|110.185.185.228|9002|China|Zhongba|CHINANET SiChuan Telecom Internet Data Center|
|18|186.232.119.58|3128|Brazil|Claudio|G4 TELECOM COMERCIO E SERVICOS DE INFORMATICA|
|19|94.237.3.45|8086|Singapore|Singapore|UpCloud Ltd|
|20|203.210.85.135|8080|Indonesia|Bandung|Infrastruktur STARNET|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


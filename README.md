
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6123** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|660|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|660|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|660|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1341|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|769|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2762|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|5.39.105.211|3128|France|Lyon|OVH SAS|
|2|45.233.67.209|999|Guatemala|Jalapa|Conectividad Y Tecnologia S.A|
|3|51.159.115.233|3128|France|Paris|SCALEWAY|
|4|75.126.253.8|8080|United States|Dallas|SoftLayer|
|5|163.172.37.158|9741|France|Vitry-sur-Seine|Online S.A.S.|
|6|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|7|66.42.53.233|8000|Singapore|Singapore|The Constant Company|
|8|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|9|51.91.100.252|443|France|Strasbourg|OVH SAS|
|10|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|172.105.216.60|443|Japan|Tokyo|Linode, LLC|
|13|134.238.252.143|8080|India|Mumbai|Google LLC|
|14|146.190.108.4|8118|Singapore|Singapore|DigitalOcean|
|15|103.137.110.58|99|Indonesia|Kepuh|PT. Capoeng Digital Nusantara|
|16|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|17|45.171.144.221|8080|Brazil|Chapadao Do Sul|N3 SOLUCOES TECNOLOGICAS LTDA|
|18|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|19|216.176.187.99|8889|United States|Los Angeles|Wowrack.com|
|20|159.89.132.108|8989|United States|Santa Clara|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


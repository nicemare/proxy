
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5013** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|304|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|304|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|304|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|775|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|486|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2501|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|13.114.216.75|80|Japan|Tokyo|Amazon Technologies Inc|
|3|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|4|45.152.188.248|3128|United States|Ashburn|Sprint|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|45.152.188.248|3128|United States|Ashburn|Sprint|
|7|45.152.188.16|3128|United States|Ashburn|Sprint|
|8|45.152.188.16|3128|United States|Ashburn|Sprint|
|9|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|144.24.238.60|8118|Switzerland|Zurich|Oracle Corporation|
|12|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|13|101.109.10.103|8080|Thailand|Ko Chan|TOT Public Company Limited|
|14|143.137.235.210|8080|Brazil|Berilo|INFORMATICA.COM LTDA|
|15|82.99.238.75|808|Iran|Khorramshahr|ParsOnline Co|
|16|193.141.65.48|808|Iran|Tehran|Green Web Samaneh Novin Co Ltd|
|17|201.222.45.54|999|Chile|Santiago|GRUPO ULLOA SpA|
|18|160.16.130.191|3128|Japan|Tokyo|SAKURA Internet Inc.|
|19|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|20|46.249.122.1|8080|Iran|Kerman|Didehban Net Company|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


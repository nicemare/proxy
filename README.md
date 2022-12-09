
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4410** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|131|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|131|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|131|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|500|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|277|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2382|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|3|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|4|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|5|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|6|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|81.181.109.143|2019|France|Paris|Virtono Networks SRL|
|9|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|10|177.93.36.50|999|Colombia|Pasto|TV AZTECA SUCURSAL COLOMBIA|
|11|179.189.125.222|8080|Brazil|Parnaiba|IP CARRIER BRASIL|
|12|181.113.225.178|80|Ecuador|Guayaquil|Corporacion Nacional De Telecomunicaciones - CNT EP|
|13|94.103.85.88|9300|Russia|Moscow|VDSINA|
|14|36.90.104.50|3128|Indonesia|Samarinda|PT. Telekomunikasi Indonesia|
|15|181.215.178.67|1337|Netherlands|Amsterdam|NovoServe B.V.|
|16|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|17|181.215.178.59|1337|Netherlands|Amsterdam|NovoServe B.V.|
|18|49.156.47.162|8080|Cambodia|Phnom Penh|WiCAM Corporation Ltd|
|19|160.16.130.191|3128|Japan|Tokyo|SAKURA Internet Inc.|
|20|1.10.141.115|8080|Thailand|Khwaeng Thung Song Hong|TOT Public Company Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


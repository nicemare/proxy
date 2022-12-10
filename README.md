
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4514** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|226|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|226|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|226|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|593|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|282|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2388|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.152.188.248|3128|United States|Ashburn|Sprint|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|54.202.43.221|3128|United States|Portland|Amazon.com, Inc.|
|4|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|5|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|6|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|45.152.188.248|3128|United States|Ashburn|Sprint|
|9|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|10|54.202.43.221|3128|United States|Portland|Amazon.com, Inc.|
|11|181.215.178.67|1337|Netherlands|Amsterdam|NovoServe B.V.|
|12|115.96.208.124|8080|India|Mumbai|Hathway IP over Cable Internet Access|
|13|177.82.85.209|3128|Brazil|Ribeirão Preto|Claro NXT Telecomunicacoes Ltda|
|14|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|15|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|16|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|17|36.94.58.26|4480|Indonesia|Tangerang|PT. Telekomunikasi Indonesia|
|18|1.10.237.12|8080|Thailand|Nakhon Pathom|TOT Public Company Limited|
|19|181.209.95.13|999|Argentina|Corrientes|ARSAT - Empresa Argentina de Soluciones Satelitales S.A|
|20|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


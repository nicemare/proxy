
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4530** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|221|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|221|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|221|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|552|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|377|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2350|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|187.251.107.143|8080|Mexico|Macuspana|Total Play Telecomunicaciones SA De CV|
|4|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|173.82.252.145|3129|United States|Portland|Multacom Corporation|
|7|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|8|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|9|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|10|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|11|134.238.252.143|8080|India|Mumbai|Google LLC|
|12|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|13|5.58.110.249|8080|Ukraine|Ternopil|Columbus|
|14|181.215.178.58|1337|Netherlands|Amsterdam|NovoServe B.V.|
|15|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|16|173.82.252.145|3129|United States|Portland|Multacom Corporation|
|17|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|
|18|3.126.79.210|3128|Germany|Frankfurt am Main|Amazon Technologies Inc.|
|19|204.199.174.60|999|Peru|Arequipa|Fiberred Sociedad Anonima Cerrada|
|20|176.99.2.43|1081|Russia|Moscow|"Domain names registrar REG.RU", Ltd|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


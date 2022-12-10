
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5559** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|542|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|542|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|542|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1106|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|620|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2582|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.152.188.248|3128|United States|Ashburn|Sprint|
|2|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|3|159.89.132.167|8989|United States|Santa Clara|DigitalOcean, LLC|
|4|75.126.253.8|8080|United States|Dallas|SoftLayer|
|5|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|6|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|7|139.28.37.94|8080|Ukraine|Kyiv|Zemlyaniy Dmitro Leonidovich|
|8|51.159.115.233|3128|France|Paris|SCALEWAY|
|9|45.152.188.248|3128|United States|Ashburn|Sprint|
|10|75.126.253.8|8080|United States|Dallas|SoftLayer|
|11|51.79.50.31|9300|Canada|Beauharnois|OVH SAS|
|12|177.82.85.209|3128|Brazil|Ribeirão Preto|Claro NXT Telecomunicacoes Ltda|
|13|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|14|194.195.90.215|8118|Singapore|Singapore|Contabo Asia Private Limited|
|15|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|16|176.10.97.97|8118|Switzerland|Zurich|Datasource AG|
|17|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|18|212.46.230.102|6969|Russia|Moscow|PJSC "Vimpelcom"|
|19|51.79.50.22|9300|Canada|Beauharnois|OVH SAS|
|20|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


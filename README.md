
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5006** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|368|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|368|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|368|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|964|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|403|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2688|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|135.148.95.28|3128|United States|Reston|OVH SAS|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|94.63.67.189|3129|Portugal|Lisbon|Vodafone Portugal|
|4|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|5|187.154.15.118|999|Mexico|Oaxaca City|Uninet S.A. de C.V.|
|6|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|7|185.81.98.16|3131|Netherlands|Naaldwijk|WorldStream B.V.|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|204.199.131.198|999|Chile|Santiago|Level 3 Communications, Inc.|
|10|43.231.0.40|7890|Hong Kong|Victoria|BUILDCLOUD|
|11|45.234.6.178|6666|Brazil|Caiaponia|Josuel Francisco De Oliveira - ME|
|12|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|13|201.222.44.227|999|Chile|Graneros|GRUPO ULLOA SpA|
|14|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|15|201.222.44.230|999|Chile|Graneros|GRUPO ULLOA SpA|
|16|185.123.101.174|4443|Turkey|Bursa|DGN TEKNOLOJI A.S.|
|17|201.222.44.106|999|Chile|Santiago|GRUPO ULLOA SpA|
|18|188.133.188.60|8080|Russia|Moscow|JSC "ER-Telecom Holding"|
|19|157.245.222.183|80|United States|Clifton|DigitalOcean, LLC|
|20|105.214.97.69|8080|South Africa|Randburg|MTN SA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


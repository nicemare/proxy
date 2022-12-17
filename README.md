
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5600** proxies at the latest update. Usable proxies are below.

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1263|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|331|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2755|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|135.148.95.28|3128|United States|Reston|OVH SAS|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|188.40.96.177|8118|Germany|Falkenstein|Hetzner Online GmbH|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|6|138.201.125.229|8118|Germany|Falkenstein|Hetzner Online GmbH|
|7|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|147.28.128.197|3128|United States|Ashburn|Packet Host, Inc.|
|10|135.148.95.28|3128|United States|Reston|OVH SAS|
|11|137.184.123.246|8080|United States|Santa Clara|DigitalOcean, LLC|
|12|75.126.253.8|8080|United States|Dallas|SoftLayer|
|13|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|14|137.184.123.246|8080|United States|Santa Clara|DigitalOcean, LLC|
|15|164.92.73.145|3128|United States|Santa Clara|DigitalOcean, LLC|
|16|154.16.180.182|3128|United States|Dulles|LYIT Internet Services|
|17|158.69.71.245|9300|Canada|Montreal|OVH SAS|
|18|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|19|85.25.4.27|8646|France|Strasbourg|Host Europe GmbH|
|20|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


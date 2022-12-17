
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6081** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|632|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|632|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|632|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1073|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1002|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2755|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|137.184.123.246|8080|United States|Santa Clara|DigitalOcean, LLC|
|3|135.148.95.28|3128|United States|Reston|OVH SAS|
|4|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|5|51.159.115.233|3128|France|Paris|SCALEWAY|
|6|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|7|179.96.28.58|80|Brazil|Calcilandia|G8 NETWORKS LTDA|
|8|75.126.253.8|8080|United States|Dallas|SoftLayer|
|9|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|10|164.92.73.145|3128|United States|Santa Clara|DigitalOcean, LLC|
|11|135.148.95.28|3128|United States|Reston|OVH SAS|
|12|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|13|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|14|137.184.123.246|8080|United States|Santa Clara|DigitalOcean, LLC|
|15|134.238.252.143|8080|India|Mumbai|Google LLC|
|16|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|17|147.28.128.197|3128|United States|Ashburn|Packet Host, Inc.|
|18|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|19|172.105.216.60|443|Japan|Tokyo|Linode, LLC|
|20|154.16.180.182|3128|United States|Dulles|LYIT Internet Services|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


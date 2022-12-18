
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5307** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|403|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|403|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|403|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|947|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|618|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2491|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|3|51.159.115.233|3128|France|Paris|SCALEWAY|
|4|163.172.37.158|9741|France|Vitry-sur-Seine|Online S.A.S.|
|5|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|6|75.126.253.8|8080|United States|Dallas|SoftLayer|
|7|109.194.101.128|3128|Russia|Yoshkar-Ola|CJSC "ER-Telecom Holding" Yoshkar-Ola branch|
|8|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|9|101.109.176.29|8080|Thailand|Ban Khao Yoi|TOT Public Company Limited|
|10|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|11|103.167.170.155|8181|Indonesia|Tangerang|PT Rajeg Media Telekomunikasi|
|12|45.125.217.90|5555|Hong Kong|Hong Kong|PINGNET|
|13|62.140.233.192|41258|Russia|Fryazino|Fryazino.net|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|202.181.14.23|3128|Bangladesh|Dhaka|BDPEER|
|16|182.253.45.29|8080|Indonesia|Jakarta|BIZNET|
|17|192.155.95.228|10801|United States|Atlanta|Linode, LLC|
|18|70.186.128.126|8080|United States|Shawnee|Cox Communications Inc.|
|19|5.39.105.211|3128|France|Lyon|OVH SAS|
|20|216.176.187.99|8889|United States|Los Angeles|Wowrack.com|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


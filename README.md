
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5566** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|534|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|534|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|534|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|942|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|692|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2681|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|135.148.95.28|3128|United States|Reston|OVH SAS|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|192.155.95.228|10000|United States|Atlanta|Linode, LLC|
|4|45.152.188.248|3128|United States|Ashburn|Sprint|
|5|51.159.115.233|3128|France|Paris|SCALEWAY|
|6|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|7|192.155.95.228|10000|United States|Atlanta|Linode, LLC|
|8|135.148.95.28|3128|United States|Reston|OVH SAS|
|9|38.49.135.250|999|Mexico|Celaya|Ientc S De RL De CV|
|10|75.126.253.8|8080|United States|Dallas|SoftLayer|
|11|134.238.252.143|8080|India|Mumbai|Google LLC|
|12|45.152.188.248|3128|United States|Ashburn|Sprint|
|13|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|14|145.40.121.209|3128|Brazil|São Paulo|Packet Host, Inc.|
|15|152.89.206.217|3128|United States|Los Angeles|Clouvider Limited|
|16|145.40.121.207|3128|Brazil|São Paulo|Packet Host, Inc.|
|17|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|18|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|19|183.111.165.158|80|South Korea|Seongnam-si|Korea Telecom|
|20|173.82.153.196|16781|United States|Portland|Multacom Corporation|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


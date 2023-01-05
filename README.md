
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6738** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|729|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|729|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|729|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1731|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|750|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2906|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|2|94.103.85.88|9300|Russia|Moscow|VDSINA|
|3|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|4|34.66.5.144|8888|United States|Council Bluffs|Google LLC|
|5|116.203.201.82|8443|Germany|Nuremberg|Hetzner Online GmbH|
|6|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|7|45.170.252.116|3128|United States|Miami|ReliableSite.Net LLC|
|8|52.53.251.113|3128|United States|San Jose|Amazon.com, Inc.|
|9|51.159.115.233|3128|France|Paris|SCALEWAY|
|10|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|11|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|12|64.227.7.192|3128|United States|North Bergen|DigitalOcean, LLC|
|13|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|14|45.167.253.225|999|Mexico|San Luis Potosí City|QDS NETWORKS SA DE CV|
|15|47.243.180.142|808|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|16|140.227.61.156|23456|Japan|Osaka|InfoSphere|
|17|150.136.7.199|3128|United States|Ashburn|Oracle Corporation|
|18|45.8.179.241|1337|United Kingdom|London|Hostland LLC|
|19|143.198.56.234|443|United States|Santa Clara|DigitalOcean, LLC|
|20|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5089** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|234|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|234|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|234|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|982|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|353|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2403|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|3|134.238.252.143|8080|India|Mumbai|Google LLC|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|89.175.164.38|8080|Russia|Moscow|MTS PJSC|
|6|5.134.216.58|8080|Russia|Moscow|Wiland Network Russia|
|7|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|8|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|9|20.228.134.234|8080|United States|Boydton|Microsoft Corporation|
|10|203.115.106.84|8080|India|Greater Noida|PRIMENET|
|11|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|12|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|13|61.7.171.221|8080|Thailand|Ban Pho|CAT Telecom Public Company Limited|
|14|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|15|45.91.133.137|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|16|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|17|178.33.198.181|3128|France|Strasbourg|OVH SAS|
|18|40.85.152.26|8080|United States|San Francisco|Microsoft Corporation|
|19|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|20|212.14.243.29|8080|Palestine|Nablus|PALTEL (Palestine Telecommunications Co.).|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


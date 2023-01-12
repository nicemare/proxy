
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **7090** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|784|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|784|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|784|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1822|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|982|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2935|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|51.159.115.233|3128|France|Paris|SCALEWAY|
|2|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|3|217.64.14.171|8080|Czechia|Brno|GiTy, a.s.|
|4|207.188.11.31|80|United States|San Antonio|H5 Data Centers - Chandler LLC|
|5|158.69.71.245|9300|Canada|Montreal|OVH SAS|
|6|195.154.227.79|8000|France|Paris|Online S.A.S.|
|7|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|8|34.66.5.144|8888|United States|Council Bluffs|Google LLC|
|9|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|10|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|11|149.56.96.252|5566|Canada|Montreal|OVH SAS|
|12|47.243.121.74|3128|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|13|198.27.74.6|9300|Canada|Beauharnois|OVH SAS|
|14|47.243.167.134|8889|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|15|172.104.63.42|3128|Singapore|Singapore|Linode, LLC|
|16|5.9.139.204|20000|Germany|Falkenstein|Hetzner Online GmbH|
|17|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|18|195.201.147.185|8084|Germany|Gunzenhausen|Hetzner Online GmbH|
|19|139.59.255.37|443|Singapore|Singapore|DIGITALOCEAN|
|20|46.163.74.99|3128|France|Strasbourg|Host Europe GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


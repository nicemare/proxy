
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5033** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|407|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|407|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|407|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|0|🚫|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|904|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|587|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2606|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|103.114.162.212|31181|United States|Las Vegas|DediPath|
|2|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|3|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|103.114.162.212|31181|United States|Las Vegas|DediPath|
|6|45.152.188.248|3128|United States|Ashburn|Sprint|
|7|179.96.28.58|80|Brazil|São Paulo|G8 NETWORKS LTDA|
|8|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|9|75.126.253.8|8080|United States|Dallas|SoftLayer|
|10|45.152.188.248|3128|United States|Ashburn|Sprint|
|11|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|12|134.238.252.143|8080|India|Mumbai|Google LLC|
|13|149.62.177.106|5555|Spain|Alhaurin de la Torre|Avatel Telecom|
|14|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|15|37.112.57.47|8080|Russia|Bryansk|CJSC "ER-Telecom Holding" Bryansk branch|
|16|161.35.223.141|80|Germany|Frankfurt am Main|DigitalOcean, LLC|
|17|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|18|79.111.13.155|50625|Russia|Moscow|Net By Net Holding LLC|
|19|52.87.136.220|80|United States|Ashburn|Amazon.com, Inc.|
|20|158.140.169.86|80|Indonesia|Surabaya|MYREPUBLIC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


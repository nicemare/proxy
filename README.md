
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6464** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|355|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|355|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|355|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1302|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|746|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3033|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|128.14.140.2|11772|United States|Los Angeles|Zenlayer Inc|
|2|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|3|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|4|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|5|128.14.140.2|11772|United States|Los Angeles|Zenlayer Inc|
|6|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|7|45.86.70.163|3333|United States|Los Angeles|DediPath|
|8|89.132.144.41|9090|Hungary|Budapest|Vodafone Hungary Ltd.|
|9|171.103.58.122|8080|Thailand|Bangkok|True Internet Co., Ltd.|
|10|184.95.3.154|8888|Puerto Rico|La Fermina|PREPA Networks|
|11|152.70.252.224|8080|South Korea|Seoul|Oracle Corporation|
|12|104.192.202.11|8080|United States|St. George|InfoWest|
|13|204.83.205.117|3128|Canada|Saskatoon|Saskatchewan Telecommunications|
|14|123.207.26.110|7777|China|Shenzhen|Shenzhen Tencent Computer Systems Company Limited|
|15|103.172.120.114|8080|Indonesia|Purwodadi Grobogan|PT Digital Akses Nusantara|
|16|104.237.154.46|443|United States|Fremont|Linode, LLC|
|17|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|18|123.182.59.249|8089|China|Zhangjiakou|Chinanet|
|19|123.182.59.74|8089|China|Zhangjiakou|Chinanet|
|20|134.238.252.143|8080|India|Mumbai|Google LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


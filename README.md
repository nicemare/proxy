
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6495** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|574|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|574|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|574|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1693|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|700|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2751|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|142.4.215.171|3128|Canada|Beauharnois|OVH SAS|
|2|50.238.158.12|8080|United States|Doraville|Comcast Cable Communications, LLC|
|3|96.68.234.217|8080|United States|Springfield|Comcast Cable Communications, LLC|
|4|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|5|149.129.248.224|3128|Indonesia|Jakarta|Alibaba.com Singapore E-Commerce Private Limited|
|6|90.255.243.214|8888|United Kingdom|London|Vodafone Limited|
|7|119.8.236.97|3128|Hong Kong|Hong Kong|Huawei International Pte. Ltd.|
|8|65.21.161.114|42069|Finland|Helsinki|Hetzner Online GmbH|
|9|50.238.158.12|8080|United States|Doraville|Comcast Cable Communications, LLC|
|10|54.172.133.237|3128|United States|Ashburn|Amazon.com, Inc.|
|11|147.139.192.225|3128|Indonesia|Jakarta|Alibaba.com LLC|
|12|43.153.34.157|3128|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|13|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|14|46.31.77.223|3128|Turkey|Gaziosmanpasa|Talha Bogaz|
|15|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|16|147.139.193.92|3128|Indonesia|Jakarta|Alibaba.com LLC|
|17|86.106.181.220|18379|Netherlands|Dronten|Mvps LTD|
|18|143.198.56.234|443|United States|Santa Clara|DigitalOcean, LLC|
|19|82.115.17.188|8080|Germany|Frankfurt am Main|BitCommand LLC|
|20|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


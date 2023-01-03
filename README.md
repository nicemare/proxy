
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5426** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|405|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|405|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|405|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1033|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|413|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2629|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|2|178.33.198.181|3128|France|Strasbourg|OVH SAS|
|3|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|4|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|5|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|6|179.96.28.58|80|Brazil|Calcilandia|G8 NETWORKS LTDA|
|7|119.28.22.45|8089|Hong Kong|Hong Kong|ComsenzNet|
|8|149.255.39.225|3128|United States|Chicago|HIVELOCITY, Inc.|
|9|96.68.234.217|8080|United States|Springfield|Comcast Cable Communications, LLC|
|10|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|11|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|12|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|13|51.79.50.31|9300|Canada|Beauharnois|OVH SAS|
|14|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|15|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|
|16|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|17|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|18|188.166.232.122|443|Singapore|Singapore|DigitalOcean, LLC|
|19|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|20|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


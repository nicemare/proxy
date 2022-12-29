
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6577** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|526|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|526|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|526|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1636|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|771|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2819|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|2|142.4.215.171|3128|Canada|Beauharnois|OVH SAS|
|3|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|4|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|5|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|6|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|7|157.245.156.12|443|Singapore|Singapore|DigitalOcean, LLC|
|8|110.78.208.91|8000|Thailand|Ratchathewi|CAT Telecom Public Company Limited|
|9|143.198.193.27|443|Singapore|Singapore|DigitalOcean, LLC|
|10|185.72.196.11|3128|Poland|Torun|Data Space|
|11|198.46.143.114|8118|Canada|Hamilton|ColoCrossing|
|12|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|13|157.230.241.229|443|Singapore|Singapore|DigitalOcean, LLC|
|14|185.212.44.235|3128|Germany|Frankfurt am Main|VPS2day.com|
|15|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|16|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|17|210.245.124.131|5239|Vietnam|Ho Chi Minh City|FPT Telecom Company|
|18|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|19|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|20|129.213.95.20|80|United States|Ashburn|Oracle Corporation|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5196** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|300|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|300|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|300|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1325|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|363|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2457|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|2|143.198.56.234|443|United States|Santa Clara|DigitalOcean, LLC|
|3|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|4|143.198.193.27|443|Singapore|Singapore|DigitalOcean, LLC|
|5|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|6|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|7|103.86.50.169|8000|Thailand|Samut Prakan|Bangmod Enterprise Co.|
|8|34.84.172.172|3128|Japan|Tokyo|Google LLC|
|9|191.252.196.14|8888|Brazil|Itacoatiara|Locaweb Serviços de Internet S/A|
|10|116.98.182.223|10003|Vietnam|Hanoi|Viettel Corporation|
|11|176.192.70.58|8008|Russia|Moscow|Net By Net Holding LLC|
|12|139.59.241.101|443|Singapore|Singapore|DigitalOcean, LLC|
|13|210.245.124.131|5239|Vietnam|Ho Chi Minh City|FPT Telecom Company|
|14|103.10.68.245|10003|Vietnam|Hanoi|HVC|
|15|139.59.255.37|443|Singapore|Singapore|DIGITALOCEAN|
|16|89.107.197.164|3128|Russia|Tula|LLC TK Altair|
|17|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|18|94.60.226.255|8080|Portugal|Matosinhos Municipality|Vodafone Portugal|
|19|116.98.176.93|10003|Vietnam|Buon Ma Thuot|Viettel Corporation|
|20|103.170.120.77|10002|Vietnam|Hanoi|Httvserver Technology Company Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


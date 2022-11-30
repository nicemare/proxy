
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4512** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|229|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|229|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|229|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|660|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|232|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2269|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|20.48.39.41|80|Japan|Tokyo|Microsoft Corporation|
|6|115.96.208.124|8080|India|Mumbai|Hathway IP over Cable Internet Access|
|7|20.196.219.248|80|South Korea|Seoul|Microsoft Corporation|
|8|20.21.127.1|80|Qatar|Doha|Microsoft Corporation|
|9|2.56.62.76|3128|Turkey|Bursa|Yesilbir Bilisim Teknolojileri Bilgisayar Yayincilik Sanayi ve Ticaret Ltd. Sti|
|10|119.8.236.97|3128|Hong Kong|Hong Kong|Huawei International Pte. Ltd.|
|11|75.126.253.8|8080|United States|Dallas|SoftLayer|
|12|167.99.4.35|3128|United States|North Bergen|DigitalOcean, LLC|
|13|68.178.202.127|3128|United States|Tempe|GoDaddy.com, LLC|
|14|154.16.180.182|3128|United States|Dulles|LYIT Internet Services|
|15|170.233.240.3|3180|Brazil|Sao Goncalo|Navenet Informatica Ltda|
|16|134.238.252.143|8080|India|Mumbai|Google LLC|
|17|85.14.243.31|3128|Germany|Kamp-Lintfort|myLoc managed IT AG|
|18|43.135.156.130|59394|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|19|209.159.155.84|80|United States|Secaucus|Interserver, Inc|
|20|14.29.108.150|8998|China|Guangzhou|Chinanet|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


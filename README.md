
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6106** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|521|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|521|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|521|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1234|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|748|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2773|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|2|141.147.158.11|8080|Japan|Osaka|Oracle Corporation|
|3|93.84.68.62|3128|Belarus|Minsk|Republican Unitary Telecommunication Enterprise Beltelecom|
|4|34.84.72.91|3128|Japan|Tokyo|Google LLC|
|5|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|6|185.198.61.146|3128|Italy|Milan|Global Router LLC|
|7|206.127.254.245|3129|United States|Glendale|Spartan Host Ltd|
|8|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|9|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|10|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|11|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|12|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|13|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|14|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|15|206.127.254.245|3129|United States|Glendale|Spartan Host Ltd|
|16|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|17|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|18|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|19|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|20|107.172.73.179|7890|United States|Buffalo|ColoCrossing|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


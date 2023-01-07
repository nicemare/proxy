
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6309** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|432|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|432|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|432|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1395|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|646|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2917|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|2|38.147.160.164|8000|United States|Los Angeles|Xnnet LLC|
|3|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|4|52.23.175.222|8118|United States|Ashburn|Amazon.com, Inc.|
|5|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|6|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|7|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|8|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|9|152.70.252.224|8080|South Korea|Seoul|Oracle Corporation|
|10|64.56.216.81|8080|United States|Winona|Upchurch Telecom & Data, Inc.|
|11|38.147.160.164|8000|United States|Los Angeles|Xnnet LLC|
|12|141.147.158.11|8080|Japan|Osaka|Oracle Corporation|
|13|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|14|189.199.106.202|999|Mexico|Zamora|Mega Cable, S.A. de C.V.|
|15|192.210.196.65|9090|United States|San Jose|ColoCrossing|
|16|185.19.4.22|3128|Ukraine|Poltava|Triolan|
|17|27.79.234.36|4003|Vietnam|Hanoi|Viettel Corporation|
|18|177.153.59.181|8080|Brazil|Itacoatiara|Locaweb Serviços de Internet S/A|
|19|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|20|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


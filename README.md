
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6101** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|629|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|629|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|629|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1390|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|697|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2663|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|138.2.8.164|8000|Japan|Tokyo|Oracle Corporation|
|2|51.159.115.233|3128|France|Paris|SCALEWAY|
|3|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|4|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|5|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|6|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|7|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|8|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|9|197.245.230.122|41026|South Africa|Middelburg|Vox Telecom|
|10|34.66.5.144|8888|United States|Council Bluffs|Google LLC|
|11|202.180.20.10|55443|Indonesia|Jakarta|PT. HIPERNET INDODATA|
|12|162.211.181.130|808|United States|Los Angeles|Intercontinental Internet Data Corp|
|13|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|14|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|15|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|16|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|17|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|18|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|19|173.212.200.30|3128|Germany|Nuremberg|Contabo GmbH|
|20|171.103.58.122|8080|Thailand|Bangkok|True Internet Co., Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6312** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|512|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|512|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|512|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1156|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|947|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2858|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|3|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|4|217.66.200.154|3128|Iran|Tehran|Tose'h Fanavari Ertebabat Pasargad Arian Co. PJS|
|5|47.243.105.131|4780|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|6|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|7|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|8|157.230.241.229|443|Singapore|Singapore|DigitalOcean, LLC|
|9|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|10|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|11|180.183.97.244|8080|Thailand|Bangkok|Triple T Broadband Public Company Limited|
|12|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|13|46.0.203.186|8080|Russia|Novokuybyshevsk|JSC "ER-Telecom Holding"|
|14|46.101.13.77|80|United Kingdom|London|DigitalOcean, LLC|
|15|161.35.223.141|80|Germany|Frankfurt am Main|DigitalOcean, LLC|
|16|27.116.41.156|9898|India|Gurugram|RailTel Corporation|
|17|187.84.254.178|53382|Brazil|Pitangui|Sempre Telecomunicacoes Ltda|
|18|43.243.142.60|59916|Indonesia|Tangerang|PT. Mora Telematika Indonesia|
|19|61.178.141.146|80|China|Yuzhong Chengguanzhen|Chinanet|
|20|159.255.188.134|41258|Poland|Zamość|TOM-NET s.c. Dariusz Koper|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


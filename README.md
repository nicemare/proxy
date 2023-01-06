
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6369** proxies at the latest update. Usable proxies are below.

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1268|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1086|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2664|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|2|34.84.142.87|3128|Japan|Tokyo|Google LLC|
|3|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|4|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|5|145.40.121.155|3128|Brazil|São Paulo|Packet Host, Inc.|
|6|5.135.240.70|8080|France|Nozay|OVH SAS|
|7|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|145.40.121.157|3128|Brazil|São Paulo|Packet Host, Inc.|
|10|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|11|212.80.213.94|8080|Thailand|Nonthaburi|Siamdata Communication Co.|
|12|85.233.134.11|80|Russia|Lebyazh'ye|JSC "Uralsvyazinform"|
|13|185.198.61.146|3128|Italy|Milan|Global Router LLC|
|14|43.132.202.254|8080|Hong Kong|Hong Kong|Shenzhen Tencent Computer Systems Company Limited|
|15|46.4.242.149|3128|Germany|Falkenstein|Hetzner Online GmbH|
|16|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|17|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|18|83.171.236.79|8080|Germany|Schwielowsee|Droptop GmbH|
|19|181.94.197.42|8080|Paraguay|Asunción|Núcleo S.A.|
|20|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


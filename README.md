
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5678** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|437|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|437|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|437|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1179|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|554|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2594|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|2|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|3|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|4|181.57.167.75|3128|Colombia|Bogotá|Telmex Colombia S.A.|
|5|20.125.122.0|3128|United States|Phoenix|Microsoft Corporation|
|6|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|7|96.68.234.217|8080|United States|Springfield|Comcast Cable Communications, LLC|
|8|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|9|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|10|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|11|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|12|178.33.198.181|3128|France|Strasbourg|OVH SAS|
|13|61.198.85.224|8080|Japan|Hommachi|NSK Co., Ltd.|
|14|47.242.174.100|8000|Hong Kong|Hong Kong|Alibaba.com LLC|
|15|194.61.120.103|3128|Netherlands|Amsterdam|Serverius Holding B.V.|
|16|52.47.64.171|3128|France|Paris|Amazon Technologies Inc.|
|17|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|18|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|19|45.91.133.137|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|20|103.122.66.240|8085|Indonesia|Jakarta|PT. Jinom Network Indonesia|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6019** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|453|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|453|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|453|

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
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|778|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2734|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|90.114.27.196|3128|France|Annemasse|TVCCONV|
|2|51.159.115.233|3128|France|Paris|SCALEWAY|
|3|207.188.11.31|80|United States|San Antonio|H5 Data Centers - Chandler LLC|
|4|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|5|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|6|185.198.61.146|3128|Italy|Milan|Global Router LLC|
|7|34.66.5.144|8888|United States|Council Bluffs|Google LLC|
|8|5.9.112.247|3128|Germany|Falkenstein|Hetzner Online GmbH|
|9|207.188.11.31|80|United States|San Antonio|H5 Data Centers - Chandler LLC|
|10|94.103.85.88|9300|Russia|Moscow|VDSINA|
|11|203.150.113.132|8080|Thailand|Watthana|Internet Thailand Company Ltd.|
|12|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|13|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|14|41.186.44.106|3128|Rwanda|Kigali|MTN Rwandacell|
|15|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|16|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|17|157.245.156.12|443|Singapore|Singapore|DigitalOcean, LLC|
|18|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|19|140.227.25.191|23456|Japan|Yonabaru|InfoSphere|
|20|47.245.33.104|12345|Japan|Tokyo|Alibaba.com LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


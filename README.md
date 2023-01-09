
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5282** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|307|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|307|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|307|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|841|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|478|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2580|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|149.56.95.184|80|Canada|Montreal|OVH Hosting|
|2|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|3|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|4|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|5|178.32.145.204|3128|France|Roubaix|OVH SAS|
|6|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|7|141.147.158.11|8080|Japan|Osaka|Oracle Corporation|
|8|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|9|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|10|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|11|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|12|134.238.252.143|8080|India|Mumbai|Google LLC|
|13|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|14|45.91.133.137|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|15|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|16|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|17|212.80.213.94|8000|Thailand|Nonthaburi|Siamdata Communication Co.|
|18|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|19|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|20|185.198.61.146|3128|Italy|Milan|Global Router LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


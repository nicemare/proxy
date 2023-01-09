
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6015** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|473|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|473|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|473|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1231|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|678|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2723|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|2|47.243.167.134|8889|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|3|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|4|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|5|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|6|161.77.221.239|3129|United States|Springfield|Crocker Communications|
|7|45.8.179.242|1337|United Kingdom|London|Hostland LLC|
|8|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|9|45.8.179.241|1337|United Kingdom|London|Hostland LLC|
|10|212.80.213.94|8080|Thailand|Nonthaburi|Siamdata Communication Co.|
|11|108.187.44.49|3129|United States|Los Angeles|Leaseweb USA, Inc.|
|12|45.130.141.59|8080|United Kingdom|London|Bangmod Enterprise Co., Ltd.|
|13|159.223.14.199|443|Netherlands|Amsterdam|DigitalOcean, LLC|
|14|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|
|15|161.77.218.137|3129|United States|Springfield|Crocker Communications|
|16|108.187.44.77|3129|United States|Los Angeles|Leaseweb USA, Inc.|
|17|108.187.44.223|3129|United States|Los Angeles|Leaseweb USA, Inc.|
|18|138.99.17.98|80|Brazil|Lucas do Rio Verde|Inexa Tecnologia LTDA.|
|19|121.204.148.136|9002|China|Qingzhou|Fuzhou|
|20|91.206.15.125|3128|Russia|Moscow|OOO "Network of data-centers "Selectel"|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


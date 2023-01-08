
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6105** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|355|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|355|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|355|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1236|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|827|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2691|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|2|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|3|206.81.2.34|80|United States|North Bergen|DigitalOcean, LLC|
|4|152.70.252.224|8080|South Korea|Seoul|Oracle Corporation|
|5|141.147.158.11|8080|Japan|Osaka|Oracle Corporation|
|6|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|7|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|8|5.135.240.70|8080|France|Nozay|OVH SAS|
|9|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|10|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|11|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|12|134.238.252.143|8080|India|Mumbai|Google LLC|
|13|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|14|188.0.147.102|3128|Kazakhstan|Almaty|JSC "KazTransCom"|
|15|206.127.254.245|3129|United States|Glendale|Spartan Host Ltd|
|16|45.179.69.42|3180|Brazil|Salvador|Marktec Telecom|
|17|91.206.15.125|3128|Russia|Moscow|OOO "Network of data-centers "Selectel"|
|18|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|19|171.103.58.122|8080|Thailand|Bangkok|True Internet Co., Ltd.|
|20|195.154.114.49|8123|France|Ivry-sur-Seine|Online S.A.S.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


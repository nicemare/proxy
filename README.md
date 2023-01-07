
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6364** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|422|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|422|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|422|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1363|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|811|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2839|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|2|38.147.160.164|8000|United States|Los Angeles|Xnnet LLC|
|3|152.70.252.224|8080|South Korea|Seoul|Oracle Corporation|
|4|104.237.154.46|80|United States|Fremont|Linode, LLC|
|5|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|6|104.237.154.46|80|United States|Fremont|Linode, LLC|
|7|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|8|43.132.202.254|8080|Hong Kong|Hong Kong|Shenzhen Tencent Computer Systems Company Limited|
|9|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|10|219.99.198.175|8080|Japan|Minatomachi|NSK Co., Ltd.|
|11|5.135.240.70|8080|France|Nozay|OVH SAS|
|12|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|13|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|14|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|15|34.84.172.172|3128|Japan|Tokyo|Google LLC|
|16|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|17|83.171.236.79|8080|Germany|Schwielowsee|Droptop GmbH|
|18|134.238.252.143|8080|India|Mumbai|Google LLC|
|19|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|20|129.146.183.219|8080|United States|Phoenix|Oracle Corporation|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


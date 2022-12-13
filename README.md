
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5200** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|213|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|213|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|213|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|685|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|577|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2687|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|8.29.103.131|8080|United States|Dawsonville|North Georgia Network Cooperative, Inc|
|2|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|3|8.29.103.131|8080|United States|Dawsonville|North Georgia Network Cooperative, Inc|
|4|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|5|194.233.84.239|80|Singapore|Singapore|Contabo Asia Private Limited|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|8|159.192.249.10|8080|Thailand|Bangkok|CAT-BB|
|9|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|10|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|11|51.79.152.70|3128|Singapore|Singapore|OVH SAS|
|12|47.252.4.64|8888|United States|Charlottesville|Alibaba.com LLC|
|13|128.199.67.35|80|Singapore|Singapore|DigitalOcean, LLC|
|14|147.139.180.37|3128|Indonesia|Jakarta|Alibaba.com LLC|
|15|157.230.241.133|34193|Singapore|Singapore|DigitalOcean, LLC|
|16|51.159.28.133|8000|France|Paris|SCALEWAY|
|17|117.33.178.110|9002|China|Fenyang|CHINANET SHAANXI province Cloud Base network|
|18|117.33.157.102|9002|China|Fenyang|CHINANET SHAANXI province Cloud Base network|
|19|45.167.125.97|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|20|41.33.3.35|1981|Egypt|Cairo|TE Data|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


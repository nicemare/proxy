
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5224** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|187|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|187|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|187|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|73|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1109|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|539|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2552|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|2|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|3|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|4|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|5|112.87.140.163|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|6|112.87.140.163|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|7|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|8|112.87.140.164|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|9|195.178.197.20|8080|Russia|Podolsk|IIP|
|10|128.199.67.35|80|Singapore|Singapore|DigitalOcean, LLC|
|11|101.226.17.188|9002|China|Shanghai|China Telecom (Group)|
|12|104.154.225.3|3128|United States|Council Bluffs|Google LLC|
|13|209.166.175.201|3128|United States|Pittsburgh|CONTINENTAL BROADBAND PENNSYLVANIA, INC.|
|14|116.202.165.119|3124|Germany|Falkenstein|Hetzner Online GmbH|
|15|112.87.140.163|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|16|113.137.42.224|9002|China|Yintai|CHINANET SHAANXI province Cloud Base network|
|17|117.50.159.109|3128|China|Beijing|UCLOUD|
|18|187.17.228.98|3128|Brazil|Louveira|Lantec Comunicacao Multimidia Ltda|
|19|209.45.95.3|999|Peru|Lima|Econocable Media SAC|
|20|103.17.201.130|8080|Pakistan|Lahore|Fiberlink|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5003** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|256|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|256|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|256|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|703|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|556|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2461|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|2|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|3|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|8|89.107.197.165|3128|Russia|Tula|LLC TK Altair|
|9|200.25.254.193|54240|Colombia|Bogotá|Andinet ON Line|
|10|50.114.134.129|3128|Pakistan|Karachi|Delta Centric LLC, Comcast Cable Communications, LLC|
|11|185.218.126.155|39811|Germany|Düsseldorf|Contabo GmbH|
|12|181.129.14.163|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|13|112.198.35.69|3128|Philippines|Bacolod City|Globe Telecom|
|14|113.133.161.189|9002|China|Yintai|CHINANET SHAANXI province Cloud Base network|
|15|103.247.22.154|3127|Indonesia|Bekasi|PT wifian Solution|
|16|1.4.251.146|8080|Thailand|Chanthaburi|TOT Public Company Limited|
|17|47.252.4.64|8888|United States|Charlottesville|Alibaba.com LLC|
|18|177.174.126.203|8080|Brazil|São Paulo|Vivo|
|19|51.158.154.173|3128|France|Paris|SCALEWAY|
|20|195.154.255.194|8000|France|Vitry-sur-Seine|Online S.A.S.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6374** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|548|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|548|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|548|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1274|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|743|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3106|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|2|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|3|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|4|81.4.102.233|8081|Netherlands|Amsterdam|WeservIT|
|5|81.4.102.223|8081|Netherlands|Amsterdam|WeservIT|
|6|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|7|51.159.115.233|3128|France|Paris|SCALEWAY|
|8|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|9|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|10|64.227.23.88|8118|United States|North Bergen|DigitalOcean, LLC|
|11|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|12|134.238.252.143|8080|India|Mumbai|Google LLC|
|13|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|14|109.194.101.128|3128|Russia|Yoshkar-Ola|CJSC "ER-Telecom Holding" Yoshkar-Ola branch|
|15|103.16.215.10|10017|Vietnam|Hanoi|Httvserver Technology Company Limited|
|16|103.16.214.219|10000|Vietnam|Hanoi|TEK|
|17|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|18|195.3.246.209|3128|Ukraine|Sevastopol|Crimeacom net|
|19|212.46.230.102|6969|Russia|Moscow|PJSC "Vimpelcom"|
|20|185.15.172.212|3128|Russia|Moscow|SafeData LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


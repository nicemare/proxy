
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6134** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|516|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|516|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|516|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1471|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|726|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2986|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|2|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|3|81.4.102.223|8081|Netherlands|Amsterdam|WeservIT|
|4|209.97.152.208|8888|United States|Clifton|DigitalOcean, LLC|
|5|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|6|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|7|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|8|81.4.102.233|8081|Netherlands|Amsterdam|WeservIT|
|9|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|10|159.89.132.108|8989|United States|Santa Clara|DigitalOcean, LLC|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|13|103.242.119.88|80|India|Kolkata|Web Werks India Pvt. Ltd.|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|103.16.214.38|10002|Vietnam|Hanoi|TEK|
|16|103.10.68.199|10000|Vietnam|Hanoi|HVC|
|17|103.161.113.97|10000|Vietnam|Ho Chi Minh City|Viet Digital Technology Liability Company|
|18|168.90.255.60|999|Argentina|Zárate|Tecnocomp S.R.L.|
|19|34.134.91.130|3128|United States|Council Bluffs|Google LLC|
|20|185.120.162.28|443|Iran|Tehran|Khallagh Borhan Market Development for Creative Industries Co|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4887** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|317|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|317|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|317|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|763|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|359|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2514|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.152.188.248|3128|United States|Ashburn|Sprint|
|2|45.152.188.16|3128|United States|Ashburn|Sprint|
|3|45.152.188.248|3128|United States|Ashburn|Sprint|
|4|213.136.101.40|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|
|5|209.141.62.12|5555|United States|Las Vegas|FranTech Solutions|
|6|75.126.253.8|8080|United States|Dallas|SoftLayer|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|213.136.101.36|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|
|9|213.136.101.37|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|
|10|75.126.253.8|8080|United States|Dallas|SoftLayer|
|11|23.95.186.182|3128|United States|Washington|ColoCrossing|
|12|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|13|23.95.186.182|3128|United States|Washington|ColoCrossing|
|14|165.192.111.151|3129|United States|Seattle|SoftLayer|
|15|45.152.188.16|3128|United States|Ashburn|Sprint|
|16|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|17|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|18|148.251.150.106|3128|Germany|Falkenstein|Hetzner Online GmbH|
|19|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|20|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


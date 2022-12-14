
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5064** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|410|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|410|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|410|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|884|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|548|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2681|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|135.148.95.28|3128|United States|Reston|OVH SAS|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|141.11.184.223|3128|Netherlands|Amsterdam|RACK400 com netherlands Infrastructure|
|4|135.148.95.28|3128|United States|Reston|OVH SAS|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|8|152.89.206.217|3128|United States|Los Angeles|Clouvider Limited|
|9|103.152.232.83|8080|Indonesia|Subang|PT Kingpolah Network Solutions|
|10|43.231.0.40|7890|Hong Kong|Victoria|BUILDCLOUD|
|11|103.180.134.250|10000|Vietnam|Hanoi|Httvserver Technology Company Limited|
|12|38.10.68.235|9090|Turkey|Istanbul|Gibirnet Iletisim Hizmetleri Sanayi VE Ticaret Limited Sirketi|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|15|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|16|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|17|103.166.28.12|8181|Indonesia|Menggala|PT Global Media Data Prima|
|18|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|19|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|20|8.29.103.131|8080|United States|Dawsonville|North Georgia Network Cooperative, Inc|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


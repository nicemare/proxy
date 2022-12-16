
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5205** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|412|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|412|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|412|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|774|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|490|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2690|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|135.148.95.28|3128|United States|Reston|OVH SAS|
|3|149.56.233.29|3128|Canada|Montreal|OVH Hosting|
|4|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|5|88.99.191.127|3128|Germany|Nuremberg|Hetzner Online GmbH|
|6|135.148.95.28|3128|United States|Reston|OVH SAS|
|7|152.32.187.164|8118|Hong Kong|Central|UCLOUD INFORMATION TECHNOLOGY (HK) LIMITED|
|8|95.216.66.183|80|Finland|Helsinki|Hetzner Online GmbH|
|9|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|10|5.39.105.211|3128|France|Lyon|OVH SAS|
|11|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|12|43.231.0.40|7890|Hong Kong|Victoria|BUILDCLOUD|
|13|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|14|103.242.119.88|80|India|Kolkata|Web Werks India Pvt. Ltd.|
|15|134.238.252.143|8080|India|Mumbai|Google LLC|
|16|5.160.179.8|8080|Iran|Tehran|Respina Networks & Beyond PJSC|
|17|45.233.64.73|999|Guatemala|Guatemala City|Conectividad Y Tecnologia S.A.|
|18|49.48.91.207|8080|Thailand|Nakhon Ratchasima|Triple T Broadband Public Company Limited|
|19|189.164.91.75|10101|Mexico|Puebla City|Uninet S.A. de C.V|
|20|204.199.204.252|999|Mexico|Tlajomulco de Zuniga|Level 3 Communications, Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


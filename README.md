
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6022** proxies at the latest update. Usable proxies are below.

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
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1198|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|721|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2752|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|141.147.158.11|8080|Japan|Osaka|Oracle Corporation|
|2|152.32.187.164|8118|Hong Kong|Central|UCLOUD INFORMATION TECHNOLOGY (HK) LIMITED|
|3|128.14.140.2|11772|United States|Los Angeles|Zenlayer Inc|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|6|128.14.140.2|11772|United States|Los Angeles|Zenlayer Inc|
|7|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|8|95.0.90.243|8080|Turkey|Istanbul|Turk Telekomunikasyon Anonim Sirketi|
|9|45.189.254.225|999|Mexico|Santiago Tuxtla|Wantelco SAS de CV|
|10|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|11|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|12|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|13|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|14|185.233.203.117|3128|Netherlands|Amsterdam|Network Management Ltd|
|15|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|16|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|17|206.127.254.245|3129|United States|Glendale|Spartan Host Ltd|
|18|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|19|202.162.212.94|8080|Indonesia|Pamulang|PT Indonesia Comnets Plus|
|20|184.95.3.154|8888|Puerto Rico|La Fermina|PREPA Networks|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


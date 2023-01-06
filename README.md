
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6406** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|408|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|408|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|408|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1415|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|980|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2660|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|2|152.70.252.224|8080|South Korea|Seoul|Oracle Corporation|
|3|94.237.3.45|8086|Singapore|Singapore|UpCloud Ltd|
|4|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|5|141.147.158.11|8080|Japan|Osaka|Oracle Corporation|
|6|45.130.141.205|8080|United Kingdom|London|Bangmod Enterprise Co., Ltd.|
|7|47.242.40.192|8080|Hong Kong|Hong Kong|Alibaba.com LLC|
|8|104.237.228.229|8080|Turkey|Istanbul|NRP TEKNOLOJi LiMiTED SiRKETi|
|9|138.201.132.168|8118|Germany|Falkenstein|Hetzner Online GmbH|
|10|5.135.240.70|8080|France|Nozay|OVH SAS|
|11|1.20.207.43|8080|Thailand|Si Racha|TOT Public Company Limited|
|12|209.166.175.201|8080|United States|Pittsburgh|CONTINENTAL BROADBAND PENNSYLVANIA, INC.|
|13|82.200.237.10|8080|Kazakhstan|Atyrau|Kazakhtelecom Data Network Administration|
|14|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|15|186.136.56.77|3128|Argentina|Mar del Plata|Telecom Argentina S.A|
|16|126.125.62.15|8080|Japan|Fukuoka|Softbank BB Corp.|
|17|94.237.3.45|8086|Singapore|Singapore|UpCloud Ltd|
|18|95.56.254.139|3128|Kazakhstan|Almaty|JSC Kazakhtelecom|
|19|3.92.226.173|3128|United States|Ashburn|Amazon Technologies Inc.|
|20|18.133.134.34|3128|United Kingdom|London|Amazon Technologies Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


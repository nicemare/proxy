
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5334** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|275|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|275|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|275|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|881|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|532|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2570|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|3|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|4|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|5|105.242.158.92|3129|South Africa|Johannesburg|Vodacom ENS|
|6|206.189.151.138|80|Singapore|Singapore|DigitalOcean, LLC|
|7|23.229.80.211|3129|United States|Buffalo|B2 Net Solutions Inc.|
|8|62.171.189.81|80|Germany|Nuremberg|Contabo GmbH|
|9|23.229.80.23|3129|United States|Buffalo|B2 Net Solutions Inc.|
|10|103.163.193.65|82|India|Bongaigaon|Orbit Broadband|
|11|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|12|196.250.239.229|8787|South Africa|Cape Town|West Indian Ocean Cable Company|
|13|195.154.255.194|8000|France|Vitry-sur-Seine|Online S.A.S.|
|14|23.229.80.47|3129|United States|Buffalo|B2 Net Solutions Inc.|
|15|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|16|183.221.242.103|9443|China|Mianyang|China Mobile|
|17|80.73.87.198|59175|Russia|Yakutsk|Sakhatelecom|
|18|189.193.224.222|999|Mexico|Cuautlancingo|Mega Cable, S.A. de C.V.|
|19|207.180.252.117|2222|Germany|Nuremberg|Contabo GmbH|
|20|167.172.148.49|3128|United States|North Bergen|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


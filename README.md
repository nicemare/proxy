
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5785** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|337|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|337|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|337|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1144|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|677|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2613|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|2|5.135.240.70|8080|France|Nozay|OVH SAS|
|3|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|4|107.172.73.179|7890|United States|Buffalo|ColoCrossing|
|5|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|6|46.246.14.5|3128|Sweden|Stockholm|Portlane Network|
|7|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|8|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|9|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|12|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|13|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|14|47.243.180.142|808|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|15|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|16|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|17|141.147.158.11|8080|Japan|Osaka|Oracle Corporation|
|18|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|19|107.172.73.179|7890|United States|Buffalo|ColoCrossing|
|20|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6405** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|272|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|272|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|272|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1304|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1086|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2664|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|2|185.198.61.146|3128|Italy|Milan|Global Router LLC|
|3|134.238.252.143|8080|India|Mumbai|Google LLC|
|4|35.221.104.58|3128|Japan|Tokyo|Google LLC|
|5|104.237.154.46|80|United States|Fremont|Linode, LLC|
|6|190.119.203.220|8080|Peru|La Victoria|America Movil Peru S.A.C.|
|7|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|8|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|9|192.210.172.22|8080|United States|Los Angeles|ColoCrossing|
|10|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|11|5.58.110.249|8080|Ukraine|Ternopil|Columbus|
|12|189.129.65.8|8080|Mexico|Tuxtla Gutiérrez|Uninet S.A. de C.V|
|13|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|14|102.177.192.84|3128|Zimbabwe|Harare|Contitouch Zimbabwe|
|15|45.91.133.137|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|16|34.29.47.221|8080|United States|Council Bluffs|Google LLC|
|17|94.103.85.88|9300|Russia|Moscow|VDSINA|
|18|3.94.29.164|3128|United States|Ashburn|Amazon Technologies Inc.|
|19|95.56.147.144|8080|Kazakhstan|Astana|JSC Kazakhtelecom|
|20|51.68.208.132|3128|United Kingdom|London|OVH SAS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


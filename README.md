
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5713** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|609|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|609|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|609|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1082|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|724|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2556|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|3|52.87.136.220|80|United States|Ashburn|Amazon.com, Inc.|
|4|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|5|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|6|5.180.136.15|8118|Russia|Moscow|Network Management Ltd|
|7|119.8.236.97|3128|Hong Kong|Hong Kong|Huawei International Pte. Ltd.|
|8|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|9|45.152.188.16|3128|United States|Ashburn|Sprint|
|10|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|11|188.40.96.177|8118|Germany|Falkenstein|Hetzner Online GmbH|
|12|134.238.252.143|8080|India|Mumbai|Google LLC|
|13|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|14|45.152.188.16|3128|United States|Ashburn|Sprint|
|15|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|16|116.203.202.160|8443|Germany|Nuremberg|Hetzner Online GmbH|
|17|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|18|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|19|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|20|193.141.65.48|808|Iran|Tehran|Green Web Samaneh Novin Co Ltd|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


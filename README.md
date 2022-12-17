
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6205** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|712|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|712|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|712|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1108|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|976|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3170|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|2|135.148.95.28|3128|United States|Reston|OVH SAS|
|3|195.154.255.194|8000|France|Vitry-sur-Seine|Online S.A.S.|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|179.96.28.58|80|Brazil|Calcilandia|G8 NETWORKS LTDA|
|7|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|8|159.89.132.108|8989|United States|Santa Clara|DigitalOcean, LLC|
|9|157.100.12.138|999|Ecuador|Alamor|Telconet S.A|
|10|135.148.95.28|3128|United States|Reston|OVH SAS|
|11|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|12|45.8.179.241|1337|United Kingdom|London|HOSTLAND|
|13|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|
|14|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|15|134.238.252.143|8080|India|Mumbai|Google LLC|
|16|85.114.112.22|8080|Palestinian Territory|Gaza|Fusion Internet Services Company LLC|
|17|181.78.13.211|999|Colombia|Barranquilla|IFX Networks Argentina S.R.L|
|18|216.215.123.174|8080|United States|Houston|Logix|
|19|192.155.95.228|10000|United States|Atlanta|Linode, LLC|
|20|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


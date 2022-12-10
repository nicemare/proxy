
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5441** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|413|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|413|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|413|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1029|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|579|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2582|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|45.152.188.248|3128|United States|Ashburn|Sprint|
|4|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|5|51.159.115.233|3128|France|Paris|SCALEWAY|
|6|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|7|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|8|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|9|45.152.188.248|3128|United States|Ashburn|Sprint|
|10|137.184.123.246|8080|United States|Santa Clara|DigitalOcean, LLC|
|11|75.126.253.8|8080|United States|Dallas|SoftLayer|
|12|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|13|137.184.123.246|8080|United States|Santa Clara|DigitalOcean, LLC|
|14|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|15|107.152.42.141|3128|United States|Chicago|tzulo, inc.|
|16|160.16.130.191|3128|Japan|Tokyo|SAKURA Internet Inc.|
|17|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|18|134.238.252.143|8080|India|Mumbai|Google LLC|
|19|172.105.226.115|443|Japan|Tokyo|Linode, LLC|
|20|45.170.35.57|999|Honduras|Danli|Onda Network S de R.L|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


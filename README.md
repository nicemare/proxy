
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5223** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|415|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|415|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|415|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|954|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|517|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2501|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.152.188.248|3128|United States|Ashburn|Sprint|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|45.152.188.16|3128|United States|Ashburn|Sprint|
|4|45.152.188.248|3128|United States|Ashburn|Sprint|
|5|45.152.188.16|3128|United States|Ashburn|Sprint|
|6|75.126.253.8|8080|United States|Dallas|SoftLayer|
|7|172.105.216.60|443|Japan|Tokyo|Linode, LLC|
|8|178.170.40.253|3128|France|Boulogne-Billancourt|Ikoula Ripe|
|9|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|10|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|11|115.96.208.124|8080|India|Mumbai|Hathway IP over Cable Internet Access|
|12|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|13|62.78.48.203|8080|Russia|Lytkarino|Wellcom ISP|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|101.109.105.71|8080|Thailand|Ban Nong Sala|TOT Public Company Limited|
|16|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|17|125.99.58.110|3128|India|Mumbai|Hathway IP over Cable Internet Access|
|18|193.141.65.48|808|Iran|Tehran|Green Web Samaneh Novin Co Ltd|
|19|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|20|213.136.101.40|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


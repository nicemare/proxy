
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4576** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|259|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|259|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|259|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|560|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|309|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2456|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|64.225.8.192|80|United States|Clifton|DigitalOcean, LLC|
|3|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|4|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|5|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|6|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|7|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|8|5.61.35.147|8118|Germany|Frankfurt am Main|LeaseWeb DE|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|11|120.89.90.198|8181|Indonesia|Cianjur|PT. Java Digital Nusantara|
|12|190.8.39.61|999|Dominican Republic|La Romana|Trilogy Dominicana, S.A.|
|13|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|14|202.91.77.222|83|India|Aklera|Swift-Online|
|15|212.46.230.102|6969|Russia|Moscow|PJSC "Vimpelcom"|
|16|34.82.107.67|80|United States|The Dalles|Google LLC|
|17|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|18|45.167.125.61|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|19|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|20|75.126.253.8|8080|United States|Dallas|SoftLayer|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


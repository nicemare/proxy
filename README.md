
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5004** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|296|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|296|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|296|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|872|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|410|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2471|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|20.230.175.193|8080|United States|Quincy|Microsoft Corporation|
|3|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|4|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|5|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|6|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|7|20.230.175.193|8080|United States|Quincy|Microsoft Corporation|
|8|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|9|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|12|75.126.253.8|8080|United States|Dallas|SoftLayer|
|13|213.136.101.37|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|
|14|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|15|190.233.80.83|999|Peru|Cajamarca|Telefonica del Peru|
|16|5.160.179.8|8080|Iran|Tehran|Respina Networks & Beyond PJSC|
|17|89.107.197.165|3128|Russia|Tula|LLC TK Altair|
|18|158.69.185.37|3129|Canada|Montreal|OVH SAS|
|19|192.99.182.243|3128|United States|Newark|OVH Hosting|
|20|5.9.112.247|3128|Germany|Falkenstein|Hetzner Online GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4863** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|311|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|311|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|311|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|723|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|371|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2518|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|2|85.193.92.239|8118|Poland|Ełk|Artnet Sp. z o.o.|
|3|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|64.227.23.88|8118|United States|North Bergen|DigitalOcean, LLC|
|6|188.0.147.102|3128|Kazakhstan|Almaty|JSC "KazTransCom"|
|7|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|8|5.161.121.151|3128|United States|Ashburn|Hetzner Online GmbH|
|9|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|10|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|11|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|12|89.107.197.165|3128|Russia|Tula|LLC TK Altair|
|13|118.173.230.246|8080|Thailand|Phak Hai|TOT Public Company Limited|
|14|130.185.238.199|8089|Brazil|Campina Grande|B Host Brasil - Internet Datacenter|
|15|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|
|16|82.165.184.53|80|Germany|Essen|IONOS SE|
|17|95.154.104.147|44393|Russia|Vladivostok|Octopusnet Jurs|
|18|181.215.178.67|1337|Netherlands|Amsterdam|NovoServe B.V.|
|19|5.58.110.249|8080|Ukraine|Ternopil|Columbus|
|20|110.77.134.106|8080|Thailand|Thon Buri|CAT Telecom Public Company Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


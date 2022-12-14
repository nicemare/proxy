
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5589** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|604|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|604|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|604|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1017|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|640|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2681|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|135.148.95.28|3128|United States|Reston|OVH SAS|
|2|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|3|88.99.204.242|3128|Germany|Nuremberg|Hetzner Online GmbH|
|4|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|5|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|6|207.180.216.251|8118|Germany|Nuremberg|Contabo GmbH|
|7|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|8|51.159.115.233|3128|France|Paris|SCALEWAY|
|9|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|10|135.148.95.28|3128|United States|Reston|OVH SAS|
|11|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|12|188.0.147.102|3128|Kazakhstan|Almaty|JSC "KazTransCom"|
|13|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|14|152.89.206.217|3128|United States|Los Angeles|Clouvider Limited|
|15|212.46.230.102|6969|Russia|Moscow|PJSC "Vimpelcom"|
|16|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|17|43.231.0.40|7890|Hong Kong|Victoria|BUILDCLOUD|
|18|190.43.232.29|999|Peru|Cusco|Telefonica del Perú|
|19|158.69.71.245|9300|Canada|Montreal|OVH SAS|
|20|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


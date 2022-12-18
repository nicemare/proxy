
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5098** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|406|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|406|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|406|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|967|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|511|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2669|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|51.159.115.233|3128|France|Paris|SCALEWAY|
|2|188.0.147.102|3128|Kazakhstan|Almaty|JSC "KazTransCom"|
|3|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|4|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|5|66.42.53.233|8000|Singapore|Singapore|The Constant Company|
|6|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|7|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|8|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|9|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|10|195.225.232.4|6053|Iran|Tehran|TS Information Technology Limited|
|11|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|12|134.238.252.143|8080|India|Mumbai|Google LLC|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|45.167.125.61|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|15|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|16|190.45.251.189|3128|Chile|Santiago|VTR BANDA ANCHA S.A.|
|17|82.99.194.30|3128|Iran|Khorramshahr|ParsOnline Co.|
|18|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|19|172.105.216.60|443|Japan|Tokyo|Linode, LLC|
|20|105.174.7.254|8080|Angola|Luanda|UNITEL SA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


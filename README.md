
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4577** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|210|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|210|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|210|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|667|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|282|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2377|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|18.162.129.217|3128|Hong Kong|Hong Kong|Amazon Technologies Inc.|
|5|134.238.252.143|8080|India|Mumbai|Google LLC|
|6|181.37.179.186|999|Dominican Republic|Santo Domingo Este|Altice Dominicana S.A.|
|7|157.245.207.186|8080|United States|Tooele|DigitalOcean, LLC|
|8|172.105.226.115|443|Japan|Tokyo|Linode, LLC|
|9|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|10|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|11|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|12|177.136.218.105|8080|Brazil|Itaipulandia|M.A. Informática Ltda.|
|13|170.244.88.1|999|Venezuela|Caracas|INVERSIONES FRITZ 78 C.A.(WIFI SOLUTION)|
|14|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|15|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|16|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|17|160.16.130.191|3128|Japan|Tokyo|SAKURA Internet Inc.|
|18|149.28.95.93|8080|United States|Los Angeles|The Constant Company|
|19|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|20|45.167.125.61|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


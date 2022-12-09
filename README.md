
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5180** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|405|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|405|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|405|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|909|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|525|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2495|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.152.188.248|3128|United States|Ashburn|Sprint|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|4|139.28.37.94|8080|Ukraine|Kyiv|Zemlyaniy Dmitro Leonidovich|
|5|177.242.140.146|999|Mexico|Pajacuaran|Mega Cable, S.A. de C.V.|
|6|45.152.188.248|3128|United States|Ashburn|Sprint|
|7|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|172.105.216.60|443|Japan|Tokyo|Linode, LLC|
|10|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|11|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|12|212.112.113.178|3128|Kyrgyzstan|Bishkek|AkNet|
|13|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|14|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|15|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|16|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|17|51.159.115.233|3128|France|Paris|SCALEWAY|
|18|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|19|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|20|194.195.90.215|8118|Singapore|Singapore|Contabo Asia Private Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5304** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|424|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|424|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|424|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|838|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|535|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2580|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|4|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|5|157.100.12.138|999|Ecuador|Loja|Telconet S.A|
|6|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|7|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|8|75.126.253.8|8080|United States|Dallas|SoftLayer|
|9|170.178.220.210|3128|United States|Santa Clarita|Multacom Corporation|
|10|177.141.99.50|8080|Brazil|São Paulo|Claro NXT Telecomunicacoes Ltda|
|11|75.72.55.108|8118|United States|Hopkins|Comcast Cable Communications, LLC|
|12|145.40.121.21|3128|Brazil|São Paulo|Packet Host, Inc.|
|13|134.238.252.143|8080|India|Mumbai|Google LLC|
|14|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|15|181.78.10.10|999|Colombia|El Zarzal|IFX Networks Argentina S.R.L|
|16|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|17|183.88.185.116|8080|Thailand|Bangkok|Triple T Broadband Public Company Limited|
|18|172.105.216.60|443|Japan|Tokyo|Linode, LLC|
|19|158.69.53.98|9300|Canada|Montreal|OVH SAS|
|20|94.103.85.88|9300|Russia|Moscow|VDSINA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


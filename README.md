
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4772** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|250|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|250|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|250|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|664|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|465|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2392|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|185.216.177.81|8118|Germany|Karlsruhe|netcup GmbH|
|2|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|3|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|4|145.40.121.157|3128|Brazil|São Paulo|Packet Host, Inc.|
|5|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|182.253.141.223|8080|Indonesia|Semarang|Biznet Networks|
|8|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|9|138.117.228.12|999|Guatemala|Huehuetenango|Fibernet S.A|
|10|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|11|45.70.6.231|8080|Brazil|Serra Talhada|OLITECH INFORMÁTICA E COMUNICAÇÃO LTDA|
|12|179.57.1.172|999|Chile|Temuco|Telefonica del Sur S.A.|
|13|145.40.121.91|3128|Brazil|São Paulo|Packet Host, Inc.|
|14|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|15|41.159.154.43|3128|Gabon|Libreville|Gabon Telecom Internet Network Autonomous System|
|16|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|17|67.52.175.140|8080|United States|Yucaipa|Spectrum|
|18|45.167.125.97|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|19|103.235.199.179|9812|Nepal|Dhulikhel|CCNEP|
|20|201.71.2.49|999|Venezuela|Caracas|Level 3 Communications, Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


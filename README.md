
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4313** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|256|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|256|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|256|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|478|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|302|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2182|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|130.18.255.115|8080|United States|Starkville|Mississippi State University|
|3|49.51.90.57|3128|Canada|Barrie|OPHL|
|4|43.135.156.58|59394|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|5|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|6|141.94.137.176|1337|France|Gravelines|OVH SAS|
|7|43.135.156.58|59394|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|8|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|9|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|10|130.18.255.115|8080|United States|Starkville|Mississippi State University|
|11|43.135.157.80|59394|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|12|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|13|43.135.157.80|59394|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|14|87.247.186.105|80|Iran|Tehran|Insightometrics B.V.|
|15|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|16|93.125.65.212|3128|Belarus|Minsk|TELECOMAT|
|17|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|18|134.238.252.143|8080|India|Mumbai|Google LLC|
|19|117.251.103.186|8080|India|Noida|BSNL Internet|
|20|200.25.254.193|54240|Colombia|Bogotá|Andinet ON Line|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


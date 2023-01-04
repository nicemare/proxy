
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6265** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|640|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|640|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|640|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1527|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|682|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2705|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|2|34.84.56.140|3128|Japan|Tokyo|Google LLC|
|3|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|4|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|5|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|6|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|7|155.133.26.123|8080|Germany|Düsseldorf|Contabo GmbH|
|8|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|9|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|10|195.201.147.185|8084|Germany|Gunzenhausen|Hetzner Online GmbH|
|11|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|
|12|51.159.115.233|3128|France|Paris|SCALEWAY|
|13|35.221.104.199|3128|Japan|Tokyo|Google LLC|
|14|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|15|203.115.106.84|8080|India|Greater Noida|PRIMENET|
|16|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|17|201.238.248.139|9229|Chile|Santiago|Gtd Internet S.A|
|18|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|19|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|20|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


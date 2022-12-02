
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4823** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|422|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|422|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|422|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|706|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|376|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2390|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|51.103.50.109|8000|France|Paris|Microsoft|
|4|45.8.179.241|1337|United Kingdom|London|HOSTLAND|
|5|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|
|6|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|7|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|8|185.156.98.70|30001|Denmark|Tønder|WNB A/S|
|9|51.11.209.150|8000|France|Paris|Microsoft|
|10|217.67.190.154|3128|Russia|Moscow|Mastertel ISP|
|11|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|12|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|
|13|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|14|20.250.26.145|8000|Switzerland|Zurich|Microsoft Corporation|
|15|157.100.12.138|999|Ecuador|Loja|Telconet S.A|
|16|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|17|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|18|158.69.53.98|9300|Canada|Montreal|OVH SAS|
|19|45.167.125.61|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|20|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


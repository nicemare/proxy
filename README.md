
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4994** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|317|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|317|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|317|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|844|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|455|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2412|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|2|198.144.149.82|3128|Canada|Toronto|Netminders Server Hosting|
|3|174.138.116.12|80|United States|Clifton|DigitalOcean, LLC|
|4|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|5|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|6|51.159.115.233|3128|France|Paris|SCALEWAY|
|7|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|8|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|9|51.178.56.44|3128|France|Gravelines|OVH SAS|
|10|20.113.40.250|3128|Germany|Frankfurt am Main|Microsoft Corporation|
|11|174.138.116.12|80|United States|Clifton|DigitalOcean, LLC|
|12|85.14.243.31|3128|Germany|Kamp-Lintfort|myLoc managed IT AG|
|13|135.181.22.40|3128|Finland|Helsinki|Hetzner Online GmbH|
|14|185.204.216.70|3128|Poland|Warsaw|Cyber_Folks S.A.|
|15|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|16|157.100.12.138|999|Ecuador|Loja|Telconet S.A|
|17|45.42.177.50|3128|United States|Ashburn|Sprint|
|18|45.167.126.78|3128|Colombia|Popayán|Sepcom Comunicaciones SAS|
|19|121.165.3.66|8080|South Korea|Suwon|Korea Telecom|
|20|134.238.252.143|8080|India|Mumbai|Google LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


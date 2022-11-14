
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4500** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|285|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|285|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|285|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|557|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|336|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2224|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|2|95.216.223.135|8888|Finland|Helsinki|Hetzner Online GmbH|
|3|3.125.238.54|8888|Germany|Frankfurt am Main|Amazon Technologies Inc.|
|4|135.181.42.136|8888|Finland|Helsinki|Hetzner Online GmbH|
|5|95.217.131.241|8888|Finland|Helsinki|Hetzner Online GmbH|
|6|65.21.54.229|8888|Finland|Helsinki|Hetzner Online GmbH|
|7|135.181.103.85|8888|Finland|Helsinki|Hetzner Online GmbH|
|8|111.90.147.212|8118|Malaysia|Kuantan|Shinjiru Technology Sdn Bhd|
|9|95.217.3.147|8888|Finland|Helsinki|Hetzner Online GmbH|
|10|117.251.103.186|8080|India|Hazratpur|BSNL Internet|
|11|154.0.171.221|3128|South Africa|Sandton|Afrihost (Pty) Ltd|
|12|95.217.23.223|8888|Finland|Helsinki|Hetzner Online GmbH|
|13|161.35.223.141|80|Germany|Frankfurt am Main|DigitalOcean, LLC|
|14|135.181.103.249|8888|Finland|Helsinki|Hetzner Online GmbH|
|15|203.150.113.37|8080|Thailand|Watthana|Internet Thailand Company Ltd.|
|16|95.216.136.105|8888|Finland|Helsinki|Hetzner Online GmbH|
|17|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|18|139.162.87.43|443|Japan|Tokyo|Linode, LLC|
|19|190.107.234.133|999|Ecuador|Quevedo|CINECABLE TV|
|20|143.137.83.137|999|Dominican Republic|San Francisco de Macorís|Teleoperadora Del Nordeste S.R.L|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


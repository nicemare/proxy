
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5526** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|409|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|409|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|409|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|974|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|541|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2728|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|3|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|4|77.247.126.194|3128|United States|Los Angeles|Clouvider Limited|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|7|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|8|77.247.126.194|3128|United States|Los Angeles|Clouvider Limited|
|9|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|10|147.139.191.249|3128|Indonesia|Jakarta|Alibaba.com LLC|
|11|134.238.252.143|8080|India|Mumbai|Google LLC|
|12|139.59.65.178|443|India|Bengaluru|DIGITALOCEAN|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|15|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|16|47.244.2.19|3128|Hong Kong|Central|Alibaba.com LLC|
|17|159.65.149.152|443|India|Bengaluru|DigitalOcean, LLC|
|18|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|19|88.255.64.82|8080|Turkey|Istanbul|Turk Telekomunikasyon Anonim Sirketi|
|20|125.99.58.110|3128|India|Mumbai|Hathway IP over Cable Internet Access|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


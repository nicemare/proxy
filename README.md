
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5455** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|421|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|421|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|421|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1055|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|493|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2556|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|2|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|3|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|4|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|5|96.68.234.217|8080|United States|Springfield|Comcast Cable Communications, LLC|
|6|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|7|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|8|178.33.198.181|3128|France|Strasbourg|OVH SAS|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|13|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|14|181.143.225.173|3129|Colombia|Santiago de Cali|EPM Telecomunicaciones S.A. E.S.P.|
|15|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|16|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|17|68.183.185.62|80|Singapore|Singapore|DigitalOcean, LLC|
|18|139.59.241.101|443|Singapore|Singapore|DigitalOcean, LLC|
|19|101.32.184.53|3128|Hong Kong|Hong Kong|Shenzhen Tencent Computer Systems Company Limited|
|20|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


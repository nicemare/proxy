
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6356** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|607|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|607|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|607|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1442|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|689|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2874|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|2|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|3|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|4|94.237.3.45|8086|Singapore|Singapore|UpCloud Ltd|
|5|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|6|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|7|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|8|23.82.16.149|3128|United States|San Jose|Leaseweb USA, Inc.|
|9|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|10|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|11|178.128.21.132|443|Singapore|Singapore|DigitalOcean, LLC|
|12|206.189.22.24|443|United Kingdom|London|DigitalOcean, LLC|
|13|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|14|46.101.13.77|80|United Kingdom|London|DigitalOcean, LLC|
|15|45.177.55.102|999|Dominican Republic|Santiago de los Caballeros|Ingenieria EN Servicios De Telecomunicaciones Agml SRL|
|16|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|17|103.240.161.109|6666|India|Patan|GTPLJAYSANTOSHIMANETWORKPVTLTD|
|18|12.218.209.130|53281|United States|Salinas|AT&T Services, Inc.|
|19|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|20|23.82.16.149|3128|United States|San Jose|Leaseweb USA, Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


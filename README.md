
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6027** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|415|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|415|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|415|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1425|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|677|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2674|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|66.42.53.233|8000|Singapore|Singapore|The Constant Company|
|2|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|3|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|146.190.108.4|8118|Singapore|Singapore|DigitalOcean|
|6|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|7|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|8|138.201.125.229|8118|Germany|Falkenstein|Hetzner Online GmbH|
|9|51.79.50.31|9300|Canada|Beauharnois|OVH SAS|
|10|192.155.95.228|10801|United States|Atlanta|Linode, LLC|
|11|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|12|188.132.222.50|8080|Turkey|Orhanlı|High Speed Telekomunikasyon ve Hab. Hiz. Ltd. Sti.|
|13|188.0.147.102|3128|Kazakhstan|Almaty|JSC "KazTransCom"|
|14|181.78.15.105|999|Colombia|Bogotá|IFX Networks Argentina S.R.L|
|15|143.244.133.78|80|India|Bengaluru|DigitalOcean, LLC|
|16|201.71.2.142|999|Venezuela|Caracas|Level 3 Communications, Inc.|
|17|47.242.37.241|3128|Hong Kong|Hong Kong|Alibaba.com LLC|
|18|5.160.179.8|8080|Iran|Tehran|Respina Networks & Beyond PJSC|
|19|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|20|201.184.145.59|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


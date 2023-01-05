
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6287** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|503|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|503|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|503|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1447|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|690|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2799|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|2|34.84.56.140|3128|Japan|Tokyo|Google LLC|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|5|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|6|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|7|209.97.152.208|8888|United States|Clifton|DigitalOcean, LLC|
|8|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|9|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|10|47.242.174.100|8000|Hong Kong|Hong Kong|Alibaba.com LLC|
|11|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|12|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|13|206.189.22.24|443|United Kingdom|London|DigitalOcean, LLC|
|14|143.198.193.27|443|Singapore|Singapore|DigitalOcean, LLC|
|15|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|16|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|17|158.69.53.98|9300|Canada|Montreal|OVH SAS|
|18|139.180.189.101|3128|Singapore|Singapore|The Constant Company|
|19|134.238.252.143|8080|India|Mumbai|Google LLC|
|20|212.14.243.29|8080|Palestine|Nablus|PALTEL (Palestine Telecommunications Co.).|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


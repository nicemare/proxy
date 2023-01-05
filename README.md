
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6144** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|558|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|558|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|558|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1216|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|686|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2891|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|2|47.243.180.142|808|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|3|51.159.115.233|3128|France|Paris|SCALEWAY|
|4|173.249.198.244|8080|United States|San Jose|tzulo, inc.|
|5|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|6|51.79.50.22|9300|Canada|Beauharnois|OVH SAS|
|7|51.159.28.133|8000|France|Paris|SCALEWAY|
|8|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|9|151.248.115.5|3128|Russia|Moscow|Reg.Ru|
|10|173.82.206.48|3128|United States|Los Angeles|Multacom Corporation|
|11|109.207.76.37|8080|Israel|Petah Tikva|O.M.C. COMPUTERS & COMMUNICATIONS LTD|
|12|52.53.251.113|3128|United States|San Jose|Amazon.com, Inc.|
|13|110.34.3.229|3128|Nepal|Kathmandu|SUBISU C7|
|14|212.14.243.29|8080|Palestine|Nablus|PALTEL (Palestine Telecommunications Co.).|
|15|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|16|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|17|12.218.209.130|53281|United States|Salinas|AT&T Services, Inc.|
|18|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|19|159.223.14.199|443|Netherlands|Amsterdam|DigitalOcean, LLC|
|20|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


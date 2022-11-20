
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4720** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|371|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|371|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|371|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|861|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|360|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2216|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|18.215.98.199|3128|United States|Ashburn|Amazon.com, Inc.|
|2|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|3|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|4|18.215.98.199|3128|United States|Ashburn|Amazon.com, Inc.|
|5|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|6|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|7|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|10|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|11|122.49.208.230|3128|Philippines|San Juan|WifiCity, Inc|
|12|51.159.115.233|3128|France|Paris|SCALEWAY|
|13|182.253.131.40|8080|Indonesia|Jakarta|BIZNET|
|14|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|
|15|128.199.110.230|443|Singapore|Singapore|DigitalOcean, LLC|
|16|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|17|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|18|183.89.119.179|8080|Thailand|Ban Nong Sala|Triple T Broadband Public Company Limited|
|19|212.154.82.52|9090|Turkey|Bodrum|TurkNet Iletisim Hizmetleri|
|20|203.253.142.180|8080|South Korea|Yuseong|KISTI|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


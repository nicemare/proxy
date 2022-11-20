
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5591** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|499|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|499|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|499|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1133|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|722|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2453|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|2|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|3|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|4|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|5|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|6|51.159.115.233|3128|France|Paris|SCALEWAY|
|7|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|8|121.165.3.66|8080|South Korea|Suwon|Korea Telecom|
|9|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|185.237.99.218|61443|United Kingdom|London|Kamatera Inc|
|12|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|13|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|14|15.235.143.16|8118|Singapore|Singapore|OVH SAS|
|15|103.189.235.91|3128|Singapore|Singapore|Cloud Host Pte Ltd|
|16|103.191.92.177|3128|Indonesia|Genuksari|PT Cloud Hosting Indonesia|
|17|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|18|197.251.233.124|8080|Ghana|Accra|Vodafone Ghana AS International Transit|
|19|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|
|20|202.144.157.1|9009|Bhutan|Thimphu|Bhutan Telecom Ltd|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


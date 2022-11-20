
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4493** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|239|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|239|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|239|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|602|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|392|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2216|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|2|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|3|149.56.233.29|3128|Canada|Montreal|OVH Hosting|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|187.188.17.138|1994|Mexico|Querétaro City|Total Play Telecomunicaciones SA De CV|
|6|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|7|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|8|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|11|103.42.162.50|8080|India|Dombivali|ADVANT|
|12|185.104.112.148|3128|Poland|Ełk|Timeweb-Artnet|
|13|38.25.184.63|999|Venezuela|Maracaibo|Airtek Solutions C.A.|
|14|94.103.85.88|9300|Russia|Moscow|VDSINA|
|15|89.107.197.165|3128|Russia|Tula|LLC TK Altair|
|16|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|17|103.175.46.134|3125|Indonesia|Sumber|PT Internet Keluarga Indonesia|
|18|70.60.230.8|9797|United States|Mount Airy|Spectrum|
|19|134.236.78.77|8080|Thailand|Hua Sai|CAT-BB|
|20|103.233.156.44|8080|Indonesia|Jakarta|PT. Mora Telematika Indonesia|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


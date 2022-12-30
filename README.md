
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5959** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|95|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|95|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|95|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1259|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|706|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2643|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|50.238.158.12|8080|United States|Doraville|Comcast Cable Communications, LLC|
|3|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|4|168.235.85.81|18888|United States|Los Angeles|InMotion Hosting, Inc.|
|5|45.170.252.116|3128|United States|Miami|ReliableSite.Net LLC|
|6|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|7|116.105.26.189|4145|Vietnam|Da Nang|Viettel Corporation|
|8|116.105.174.204|4153|Vietnam|Da Nang|Viettel Corporation|
|9|116.105.173.243|4145|Vietnam|Da Nang|Viettel Corporation|
|10|116.105.173.243|4145|Vietnam|Da Nang|Viettel Corporation|
|11|116.105.26.189|4145|Vietnam|Da Nang|Viettel Corporation|
|12|116.105.26.189|4145|Vietnam|Da Nang|Viettel Corporation|
|13|116.105.173.243|4145|Vietnam|Da Nang|Viettel Corporation|
|14|116.105.173.243|4145|Vietnam|Da Nang|Viettel Corporation|
|15|212.120.170.90|8123|Russia|Perm|PERMONLINE|
|16|20.121.184.238|80|United States|Boydton|Microsoft Corporation|
|17|222.124.202.144|8080|Indonesia|Serang|PT. TELKOM INDONESIA|
|18|194.145.138.14|9090|Turkey|Istanbul|Atlantis Telekomunikasyon Bilisim Hizmetleri San. Tic. Ltd|
|19|170.79.91.102|8080|Colombia|Ibague|TV AZTECA SUCURSAL COLOMBIA|
|20|103.180.132.223|10006|Vietnam|Hanoi|Httvserver Technology Company Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


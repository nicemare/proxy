
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4179** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|171|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|171|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|171|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|421|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|215|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2260|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|45.152.188.16|3128|United States|Ashburn|Sprint|
|4|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|5|45.152.188.248|3128|United States|Ashburn|Sprint|
|6|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|7|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|8|213.136.101.40|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|
|9|150.95.81.164|8080|Thailand|Kanchanaburi|ZCOM|
|10|45.152.188.248|3128|United States|Ashburn|Sprint|
|11|45.152.188.16|3128|United States|Ashburn|Sprint|
|12|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|13|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|14|160.16.130.191|3128|Japan|Tokyo|SAKURA Internet Inc.|
|15|184.155.36.194|8080|United States|Pocatello|CABLE ONE, INC.|
|16|116.203.202.160|8443|Germany|Nuremberg|Hetzner Online GmbH|
|17|134.238.252.143|8080|India|Mumbai|Google LLC|
|18|18.235.55.193|8080|United States|Ashburn|Amazon.com, Inc.|
|19|201.77.108.72|999|Mexico|Jimenez|Nidix Networks S.a. De C.V.|
|20|50.235.247.114|8085|United States|Ashburn|Comcast Cable Communications, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


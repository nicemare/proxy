
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4629** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|255|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|255|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|255|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|631|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|433|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2214|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|104.166.125.216|3128|United States|Los Angeles|Baxet Group Inc|
|4|88.80.187.42|3128|United Kingdom|London|Linode, LLC|
|5|159.65.120.166|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|6|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|7|75.126.253.8|8080|United States|Dallas|SoftLayer|
|8|104.166.125.216|3128|United States|Los Angeles|Baxet Group Inc|
|9|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|10|66.29.140.79|3128|Guinea|Macenta|Namecheap, Inc.|
|11|52.87.136.220|80|United States|Ashburn|Amazon.com, Inc.|
|12|45.167.125.97|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|13|134.238.252.143|8080|India|Mumbai|Google LLC|
|14|51.159.115.233|3128|France|Paris|SCALEWAY|
|15|157.100.12.138|999|Ecuador|Loja|Telconet S.A|
|16|213.241.205.2|8080|Russia|Rostov-on-Don|RTCOMM-YUG|
|17|45.167.125.61|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|18|149.56.96.252|9300|Canada|Montreal|OVH SAS|
|19|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|20|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


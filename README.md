
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4161** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|136|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|136|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|136|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|389|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|160|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2261|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|49.51.90.57|3128|Canada|Barrie|OPHL|
|4|89.40.72.158|3128|Romania|Sfantu Gheorghe|Romarg SRL|
|5|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|6|177.136.218.105|8080|Brazil|Itaipulandia|M.A. Informática Ltda.|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|51.159.28.133|8000|France|Paris|SCALEWAY|
|9|3.110.222.113|3128|India|Mumbai|Amazon Technologies Inc.|
|10|115.96.208.124|8080|India|Mumbai|Hathway IP over Cable Internet Access|
|11|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|12|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|13|51.159.115.233|3128|France|Paris|SCALEWAY|
|14|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|15|157.100.12.138|999|Ecuador|Loja|Telconet S.A|
|16|158.160.1.43|3128|Russia|Moscow|Yandex.Cloud LLC|
|17|46.101.126.180|36047|Germany|Frankfurt am Main|DigitalOcean, LLC|
|18|185.190.38.154|8080|Kosovo|Dubova|Kadri Haxhiaj trading as "B.I."|
|19|191.97.16.127|999|Venezuela|Caracas|INVERSIONES FRITZ 78 C.A.(WIFI SOLUTION)|
|20|103.231.241.102|80|Philippines|Quezon City|De La Salle University|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5094** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|384|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|384|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|384|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1240|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|354|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2549|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|3|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|4|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|7|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|8|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|9|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|10|51.159.115.233|3128|France|Paris|SCALEWAY|
|11|51.79.50.22|9300|Canada|Beauharnois|OVH SAS|
|12|165.192.111.151|3129|United States|Seattle|SoftLayer|
|13|154.16.180.182|3128|United States|Dulles|LYIT Internet Services|
|14|142.129.238.249|80|United States|Pomona|Charter Communications Inc|
|15|134.238.252.143|8080|India|Mumbai|Google LLC|
|16|185.200.36.165|8888|Turkey|Antakya|High Speed Telekomunikasyon ve Hab. Hiz. Ltd. Sti.|
|17|206.41.241.118|8080|United States|Jackson|Internet Doorway, Inc.|
|18|157.90.141.135|3128|Germany|Falkenstein|Hetzner Online GmbH|
|19|85.14.243.31|3128|Germany|Kamp-Lintfort|myLoc managed IT AG|
|20|103.161.119.210|10010|Vietnam|Ho Chi Minh City|THIENCO|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


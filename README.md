
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5506** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|356|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|356|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|356|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1110|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|620|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2825|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|3|51.75.67.164|80|Germany|Limburg an der Lahn|OVH SAS|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|47.240.1.7|27954|Hong Kong|Central|Alibaba.com LLC|
|6|82.99.194.30|3128|Iran|Khorramshahr|ParsOnline Co.|
|7|167.114.96.27|9300|Canada|Montreal|OVH SAS|
|8|51.79.50.31|9300|Canada|Beauharnois|OVH SAS|
|9|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|10|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|11|103.180.139.111|10003|Vietnam|Ho Chi Minh City|TANHOANGVINA|
|12|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|13|140.227.61.156|23456|Japan|Chiyoda-ku|InfoSphere|
|14|197.232.36.85|41890|Kenya|Nairobi|Jamii Telecommunications Limited|
|15|123.240.60.64|8888|Taiwan|Taichung|TBC|
|16|103.106.193.137|7532|India|Delhi|Elyzium Consulting|
|17|177.234.232.116|999|Ecuador|Guayaquil|Nedetel S.A.|
|18|138.124.180.188|3128|United States|Secaucus|MIRholding B.V.|
|19|143.244.133.78|80|India|Bengaluru|DigitalOcean, LLC|
|20|185.218.126.155|39811|Germany|Düsseldorf|Contabo GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


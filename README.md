
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5888** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|535|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|535|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|535|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1127|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|668|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2842|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|3.238.80.60|3128|United States|Ashburn|Amazon Technologies Inc.|
|2|18.130.234.29|3128|United Kingdom|London|Amazon Technologies Inc.|
|3|3.238.80.60|3128|United States|Ashburn|Amazon Technologies Inc.|
|4|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|5|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|6|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|7|163.172.84.250|9741|France|Paris|Online S.A.S.|
|8|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|9|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|10|149.129.223.129|3128|Indonesia|Jakarta|Alibaba.com Singapore E-Commerce Private Limited|
|11|149.129.218.191|3128|Indonesia|Jakarta|Alibaba.com Singapore E-Commerce Private Limited|
|12|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|13|103.180.132.166|10002|Vietnam|Hanoi|Httvserver Technology Company Limited|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|103.16.160.142|10000|Vietnam|Chúc Sơn|ANH|
|16|182.191.84.39|80|Pakistan|Rawalpindi|Pakistan Telecommuication company limited|
|17|158.69.53.98|9300|Canada|Montreal|OVH SAS|
|18|103.6.8.20|8080|Cambodia|Phnom Penh|Telecom Cambodia (T.C.)|
|19|202.150.132.53|8080|Indonesia|Depok|PT Comtronics Systems|
|20|103.161.97.30|10000|Vietnam|Hà Đông|MXGROUP|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


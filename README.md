
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5001** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|360|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|360|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|360|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|913|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|376|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2461|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|2|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|3|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|4|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|5|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|8|66.42.53.233|8000|Singapore|Singapore|The Constant Company|
|9|200.29.237.154|999|Colombia|Santiago de Cali|Consulnetwork Ltda|
|10|14.97.155.42|3128|India|Delhi|Tata Teleservices LTD - Tata Indicom - Cdma Division|
|11|103.16.215.10|10017|Vietnam|Hanoi|Httvserver Technology Company Limited|
|12|79.142.95.90|55443|Kazakhstan|Astana|Obit Telecommunications|
|13|186.67.192.246|8080|Chile|Temuco|Entel Chile S.A.|
|14|163.177.106.4|8001|China|Shenzhen|China Unicom Guangdong Province Network|
|15|78.158.171.59|8080|Iran|Tehran|Tose'h Fanavari Ertebabat Pasargad Arian Co. PJS|
|16|51.79.50.46|9300|Canada|Beauharnois|OVH SAS|
|17|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|18|201.71.2.142|999|Venezuela|Caracas|Level 3 Communications, Inc.|
|19|45.173.231.155|999|Ecuador|Guayaquil|Eliana Vanessa Morocho Oña|
|20|106.227.51.67|9002|China|Dunhou|China Telecom|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


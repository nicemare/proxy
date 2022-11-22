
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4366** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|115|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|115|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|115|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|530|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|166|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2319|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|2|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|3|45.167.126.78|3128|Colombia|Popayán|Sepcom Comunicaciones SAS|
|4|198.59.191.234|8080|United States|Carlsbad|TDS TELECOM|
|5|134.238.252.143|8080|India|Mumbai|Google LLC|
|6|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|7|87.247.186.105|80|Iran|Tehran|Insightometrics B.V.|
|8|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|9|75.126.253.8|8080|United States|Dallas|SoftLayer|
|10|204.185.204.64|8080|United States|Kansas City|org-morenet.more.net|
|11|75.126.253.8|8080|United States|Dallas|SoftLayer|
|12|176.126.83.189|3128|Italy|Milan|Seflow S.N.C. Di Marco Brame' & C.|
|13|135.181.22.40|3128|Finland|Helsinki|Hetzner Online GmbH|
|14|175.6.216.20|9002|China|Loudi|Hengyang|
|15|123.182.59.115|8089|China|Zhangjiakou|Chinanet|
|16|36.99.39.69|9002|China|Zhengzhou|China Telecom|
|17|1.194.236.145|9002|China|Yingchuan|China Telecom|
|18|117.33.136.41|9002|China|Fenyang|CHINANET SHAANXI province Cloud Base network|
|19|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|20|195.225.232.3|8085|Iran|Tehran|TS Information Technology Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6443** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|784|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|784|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|784|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1860|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|900|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2432|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|149.56.233.29|3128|Canada|Montreal|OVH Hosting|
|2|135.148.95.28|3128|United States|Reston|OVH SAS|
|3|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|101.32.184.53|3128|Hong Kong|Hong Kong|Shenzhen Tencent Computer Systems Company Limited|
|6|179.96.28.58|80|Brazil|Calcilandia|G8 NETWORKS LTDA|
|7|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|8|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|9|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|
|12|75.126.253.8|8080|United States|Dallas|SoftLayer|
|13|135.148.95.28|3128|United States|Reston|OVH SAS|
|14|75.126.253.8|8080|United States|Dallas|SoftLayer|
|15|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|16|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|17|193.169.253.101|3128|Poland|Warsaw|"SPRINT" S.A.|
|18|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|19|185.8.165.134|8800|Czechia|Prague|Master Internet s.r.o.|
|20|162.155.10.150|55443|United States|Strongsville|Charter Communications Inc|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


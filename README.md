
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5742** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|262|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|262|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|262|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1232|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|543|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2616|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|2|193.122.134.214|80|United States|Ashburn|Oracle Corporation|
|3|128.199.55.6|443|Netherlands|Amsterdam|DigitalOcean, LLC|
|4|187.17.228.98|3128|Brazil|Louveira|Lantec Comunicacao Multimidia Ltda|
|5|113.125.8.114|9002|China|Xintai|Cloud Computing Corporation|
|6|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|7|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|8|112.87.140.164|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|9|181.129.49.214|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|10|175.139.179.65|42580|Malaysia|Shah Alam|Telekom Malaysia Berhad|
|11|185.20.198.250|8080|Iraq|Basrah|Horizon Scope Mobile Telecom WLL|
|12|44.31.180.10|8080|France|Aubervilliers|Association Senaheberg|
|13|198.11.179.220|80|United States|Minkler|Alibaba (US) Technology Co., Ltd.|
|14|41.65.236.56|1981|Egypt|Cairo|Etisalat Misr|
|15|95.181.164.59|8080|Russia|Moscow|Yegor Andreevich trading as FLP Miglovets|
|16|144.49.96.25|8080|United States|Washington|Google LLC|
|17|145.40.121.73|3128|Brazil|São Paulo|Packet Host, Inc.|
|18|95.56.254.139|3128|Kazakhstan|Almaty|JSC Kazakhtelecom|
|19|77.236.238.33|1256|Russia|Moscow|ArtCommunications Ltd.|
|20|109.207.76.37|8080|Israel|Petah Tikva|O.M.C. COMPUTERS & COMMUNICATIONS LTD|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6404** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|518|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|518|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|518|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1424|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|815|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2814|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|3|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|4|207.188.11.31|80|United States|San Antonio|H5 Data Centers - Chandler LLC|
|5|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|6|217.64.14.171|8080|Czechia|Brno|GiTy, a.s.|
|7|34.66.5.144|8888|United States|Council Bluffs|Google LLC|
|8|47.245.33.104|12345|Japan|Tokyo|Alibaba.com LLC|
|9|207.188.11.31|80|United States|San Antonio|H5 Data Centers - Chandler LLC|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|5.9.139.204|25000|Germany|Falkenstein|Hetzner Online GmbH|
|12|47.243.167.134|8889|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|13|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|14|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|15|213.233.182.38|8000|Iran|Tehran|SHARIF-EDU|
|16|34.146.64.228|3128|Japan|Tokyo|Google LLC|
|17|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|18|158.69.27.94|9300|Canada|Montreal|OVH SAS|
|19|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|20|46.101.13.77|80|United Kingdom|London|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


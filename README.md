
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **7374** proxies at the latest update. Usable proxies are below.

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
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|2210|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|947|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3166|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|47.244.2.19|3128|Hong Kong|Central|Alibaba.com LLC|
|2|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|3|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|4|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|5|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|6|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|7|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|8|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|9|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|10|157.230.36.51|443|Singapore|Singapore|DigitalOcean, LLC|
|11|181.94.197.42|8080|Paraguay|Asunción|Núcleo S.A.|
|12|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|13|45.91.133.137|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|14|43.206.108.156|3128|Japan|Tokyo|Amazon.com, Inc.|
|15|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|16|47.243.167.134|8889|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|17|135.12.195.20|3128|United States|Sterling|Carrytel|
|18|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|19|94.20.38.130|3128|Azerbaijan|Baku|Delta Telecom|
|20|213.233.182.39|8000|Iran|Tehran|SHARIF-EDU|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


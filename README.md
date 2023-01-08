
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6329** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|512|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|512|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|512|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1412|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|829|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2737|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|5.135.240.70|8080|France|Nozay|OVH SAS|
|2|134.238.252.143|8080|India|Mumbai|Google LLC|
|3|219.99.198.175|8080|Japan|Minatomachi|NSK Co., Ltd.|
|4|212.80.213.94|8080|Thailand|Nonthaburi|Siamdata Communication Co.|
|5|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|6|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|7|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|8|146.56.171.149|3128|South Korea|Seoul|Oracle Corporation|
|9|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|10|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|11|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|12|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|13|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|14|47.243.180.142|808|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|15|108.165.228.187|3128|United States|Buffalo|Ipxo LLC|
|16|185.198.61.146|3128|Italy|Milan|Global Router LLC|
|17|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|18|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|19|152.70.252.224|8080|South Korea|Seoul|Oracle Corporation|
|20|190.186.18.161|999|Bolivia|Santa Cruz|Cotas Ltda.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


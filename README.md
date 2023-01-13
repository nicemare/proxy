
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **8088** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|747|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|747|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|747|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|2308|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1256|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3173|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|185.198.61.146|3128|Italy|Milan|Global Router LLC|
|2|51.159.115.233|3128|France|Paris|SCALEWAY|
|3|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|4|217.64.14.180|8080|Czechia|Brno|GiTy, a.s.|
|5|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|6|179.63.255.230|999|Honduras|San Pedro Sula|INET Communication|
|7|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|8|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|9|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|10|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|11|213.136.101.36|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|
|12|193.122.134.214|80|United States|Ashburn|Oracle Corporation|
|13|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|14|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|15|47.243.105.131|4780|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|16|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|17|157.230.241.229|443|Singapore|Singapore|DigitalOcean, LLC|
|18|212.80.213.94|8000|Thailand|Nonthaburi|Siamdata Communication Co.|
|19|217.219.28.117|3128|Iran|Rafsanjan|Iran Telecommunication Company PJS|
|20|162.211.181.130|808|United States|Los Angeles|Intercontinental Internet Data Corp|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


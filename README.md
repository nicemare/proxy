
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6850** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|696|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|696|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|696|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1612|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|952|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2935|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|2|207.204.241.126|8118|United States|San Francisco|Strong Technology|
|3|149.56.95.184|80|Canada|Montreal|OVH Hosting|
|4|5.9.139.204|20000|Germany|Falkenstein|Hetzner Online GmbH|
|5|217.64.14.171|8080|Czechia|Brno|GiTy, a.s.|
|6|181.94.197.42|8080|Paraguay|Asunción|Núcleo S.A.|
|7|152.32.187.164|8118|Hong Kong|Central|UCLOUD INFORMATION TECHNOLOGY (HK) LIMITED|
|8|103.148.192.83|8082|Indonesia|Bandung|PT. Akashia Thuba Jaya|
|9|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|10|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|11|209.141.62.12|5555|United States|Las Vegas|FranTech Solutions|
|12|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|13|47.245.33.104|12345|Japan|Tokyo|Alibaba.com LLC|
|14|45.32.69.105|3128|United States|Los Angeles|The Constant Company|
|15|201.238.248.139|9229|Chile|Santiago|Gtd Internet S.A|
|16|207.188.11.31|80|United States|San Antonio|H5 Data Centers - Chandler LLC|
|17|157.230.241.229|443|Singapore|Singapore|DigitalOcean, LLC|
|18|193.122.134.214|80|United States|Ashburn|Oracle Corporation|
|19|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|20|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5678** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|446|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|446|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|446|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1124|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|548|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2755|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|2|34.146.19.255|3128|Japan|Tokyo|Google LLC|
|3|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|4|152.228.206.188|80|France|Roubaix|OVH SAS|
|5|103.16.161.187|10000|Vietnam|Chúc Sơn|Httvserver Technology Company Limited|
|6|157.230.212.80|8080|United States|North Bergen|DigitalOcean, LLC|
|7|157.230.217.226|8080|United States|North Bergen|DigitalOcean, LLC|
|8|47.254.156.107|8000|Germany|Frankfurt am Main|Alibaba.com LLC|
|9|94.73.239.124|55443|Russia|Krasnoyarsk|Orion Telecom LLC|
|10|47.244.2.19|3128|Hong Kong|Central|Alibaba.com LLC|
|11|65.21.161.114|42069|Finland|Helsinki|Hetzner Online GmbH|
|12|88.218.251.189|8080|Russia|Moscow|eServer s.r.o.|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|34.84.72.91|3128|Japan|Tokyo|Google LLC|
|15|157.230.212.80|8080|United States|North Bergen|DigitalOcean, LLC|
|16|64.225.8.192|80|United States|Clifton|DigitalOcean, LLC|
|17|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|18|35.221.104.199|3128|Japan|Tokyo|Google LLC|
|19|186.208.81.214|3129|Brazil|Passo Fundo|RazaoInfo Internet Ltda|
|20|158.69.72.138|9300|Canada|Montreal|OVH SAS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


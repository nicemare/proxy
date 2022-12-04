
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4636** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|304|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|304|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|304|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|640|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|374|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2371|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|208.82.61.12|3128|United States|Ashburn|Bernardi Sounds|
|3|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|4|208.82.61.13|3128|United States|Ashburn|Bernardi Sounds|
|5|45.152.188.16|3128|United States|Ashburn|Sprint|
|6|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|
|7|75.126.253.8|8080|United States|Dallas|SoftLayer|
|8|128.199.221.6|443|Singapore|Singapore|DigitalOcean, LLC|
|9|45.152.188.16|3128|United States|Ashburn|Sprint|
|10|208.82.61.12|3128|United States|Ashburn|Bernardi Sounds|
|11|208.82.61.13|3128|United States|Ashburn|Bernardi Sounds|
|12|51.159.115.233|3128|France|Paris|SCALEWAY|
|13|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|14|201.73.228.20|3128|Brazil|Rio de Janeiro|Claro S.A|
|15|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|16|58.11.158.4|80|Thailand|Bangkok|True Internet Corporation CO. Ltd.|
|17|115.96.208.124|8080|India|Mumbai|Hathway IP over Cable Internet Access|
|18|134.238.252.143|8080|India|Mumbai|Google LLC|
|19|190.8.39.60|999|Dominican Republic|La Romana|Trilogy Dominicana, S.A.|
|20|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


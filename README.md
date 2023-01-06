
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5158** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|371|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|371|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|371|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1190|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|0|🚫|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2617|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|2|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|3|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|4|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|5|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|6|45.8.179.247|1337|United Kingdom|London|Hostland LLC|
|7|149.56.252.62|3128|Canada|Montreal|OVH Hosting|
|8|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|9|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|
|10|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|11|45.8.179.242|1337|United Kingdom|London|Hostland LLC|
|12|45.8.179.241|1337|United Kingdom|London|Hostland LLC|
|13|51.159.115.233|3128|France|Paris|SCALEWAY|
|14|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|15|159.223.14.199|443|Netherlands|Amsterdam|DigitalOcean, LLC|
|16|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|17|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|18|45.91.133.137|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|19|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|20|203.115.106.85|8080|India|Greater Noida|PRIMENET|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


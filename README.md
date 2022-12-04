
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4369** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|121|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|121|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|121|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|412|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|224|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2382|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.152.188.16|3128|United States|Ashburn|Sprint|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|208.82.61.13|3128|United States|Ashburn|Bernardi Sounds|
|4|208.82.61.12|3128|United States|Ashburn|Bernardi Sounds|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|7|208.82.61.12|3128|United States|Ashburn|Bernardi Sounds|
|8|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|9|45.152.188.16|3128|United States|Ashburn|Sprint|
|10|208.82.61.13|3128|United States|Ashburn|Bernardi Sounds|
|11|164.92.160.38|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|12|134.238.252.143|8080|India|Mumbai|Google LLC|
|13|104.166.125.216|3128|United States|Los Angeles|Baxet Group Inc|
|14|161.53.129.23|3128|Croatia|Krapinske Toplice|Croatian Academic and Research Network|
|15|51.159.115.233|3128|France|Paris|SCALEWAY|
|16|115.96.208.124|8080|India|Mumbai|Hathway IP over Cable Internet Access|
|17|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|
|18|46.101.13.77|80|United Kingdom|London|DigitalOcean, LLC|
|19|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|
|20|170.80.202.241|999|Dominican Republic|Santiago de los Caballeros|RUDDY GONZALEZ DIGITAL MEDIA DOMINICANA, RGDIMAX, S.R.L|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


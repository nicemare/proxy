
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5669** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|503|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|503|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|503|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1326|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|653|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2739|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|50.114.128.17|3128|Pakistan|Karachi|Delta Centric LLC, Comcast Cable Communications, LLC|
|2|185.39.50.2|1337|Germany|Blankenfelde|NETZNUTZ|
|3|81.4.102.233|8081|Netherlands|Amsterdam|WeservIT|
|4|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|5|81.4.102.223|8081|Netherlands|Amsterdam|WeservIT|
|6|185.217.137.242|1337|Seychelles|Cascade|Stallion Network Services Limited|
|7|185.217.137.216|1337|Seychelles|Cascade|Stallion Network Services Limited|
|8|81.4.122.143|8081|Netherlands|Alblasserdam|WeservIT|
|9|45.8.179.241|1337|United Kingdom|London|HOSTLAND|
|10|23.93.174.220|3128|United States|Oakland|Sonic Telecom LLC|
|11|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|12|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|13|23.93.174.220|3128|United States|Oakland|Sonic Telecom LLC|
|14|51.158.154.173|3128|France|Paris|SCALEWAY|
|15|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|16|14.207.128.102|8080|Thailand|Chachoengsao|Triple T Broadband Public Company Limited|
|17|45.168.65.2|8080|Brazil|São Paulo|Thiago aparecido scaramuzza santana|
|18|47.57.233.110|808|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|19|45.173.231.195|999|Ecuador|Guayaquil|Eliana Vanessa Morocho Oña|
|20|66.42.53.233|8000|Singapore|Singapore|The Constant Company|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


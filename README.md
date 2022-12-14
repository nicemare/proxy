
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4341** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|360|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|360|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|360|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|545|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|196|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2349|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|135.148.95.28|3128|United States|Reston|OVH SAS|
|2|47.251.15.176|1080|United States|Santa Clara|Alibaba.com LLC|
|3|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|4|147.28.128.197|3128|United States|Ashburn|Packet Host, Inc.|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|7|38.49.135.250|999|Mexico|Celaya|Ientc S De RL De CV|
|8|164.92.73.145|3128|United States|Santa Clara|DigitalOcean, LLC|
|9|47.251.15.176|1080|United States|Santa Clara|Alibaba.com LLC|
|10|124.83.117.215|8081|Philippines|Valenzuela|Philippine Long Distance Telephone Co.|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|181.78.13.239|999|Colombia|Barranquilla|IFX Networks Argentina S.R.L|
|13|36.90.14.8|80|Indonesia|Semarang|PT. Telekomunikasi Indonesia|
|14|45.77.44.96|8000|Singapore|Singapore|Choopa|
|15|146.59.226.20|3128|France|Gravelines|OVH SAS|
|16|1.20.207.207|8080|Thailand|Ban Nong Sala|TOT Public Company Limited|
|17|188.166.221.103|3128|Singapore|Singapore|DigitalOcean, LLC|
|18|77.247.126.194|3128|United States|Los Angeles|Clouvider Limited|
|19|145.40.121.207|3128|Brazil|São Paulo|Packet Host, Inc.|
|20|183.89.94.81|8080|Thailand|Bangkok|Triple T Broadband Public Company Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


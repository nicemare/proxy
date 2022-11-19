
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4095** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|160|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|160|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|160|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|401|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|129|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2282|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|2|172.104.60.117|3128|Singapore|Singapore|Linode, LLC|
|3|134.238.252.143|8080|India|Mumbai|Google LLC|
|4|183.89.2.64|8080|Thailand|Ban Bueng|Triple T Broadband Public Company Limited|
|5|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|6|5.58.58.209|8080|Ukraine|Ternopil|Columbus|
|7|160.16.66.87|3190|Japan|Tokyo|SAKURA Internet Inc.|
|8|183.89.154.36|8080|Thailand|Bangkok|Triple T Broadband Public Company Limited|
|9|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|10|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|
|11|122.49.208.242|3128|Philippines|San Juan|WifiCity, Inc|
|12|113.160.247.27|19132|Vietnam|Da Nang|VietNam Post and Telecom Corporation|
|13|110.77.171.189|8080|Thailand|Samphanthawong|CAT-BB|
|14|103.43.1.0|3129|Indonesia|Pondok Pinang|PT Daya Sinergi Telekomunikasi|
|15|38.49.131.146|999|Mexico|Celaya|Ientc S De RL De CV|
|16|107.152.42.141|8080|United States|Chicago|tzulo, inc.|
|17|188.121.120.185|80|Iran|Tehran|Noyan Abr Arvan Co. ( Private Joint Stock)|
|18|176.31.213.100|8080|France|La Rochelle|OVH SAS|
|19|110.78.149.181|8080|Thailand|Pathum Thani|CAT-BB|
|20|36.93.138.186|8080|Indonesia|Jakarta|Telekomunikasi Indonesia|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


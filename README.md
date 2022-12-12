
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5062** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|256|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|256|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|256|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|613|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|523|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2675|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|145.40.121.167|3128|Brazil|São Paulo|Packet Host, Inc.|
|2|134.238.252.143|8080|India|Mumbai|Google LLC|
|3|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|4|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|5|183.80.180.218|4001|Vietnam|Hanoi|FPT Telecom Company|
|6|188.0.147.102|3128|Kazakhstan|Almaty|JSC "KazTransCom"|
|7|181.238.40.29|8080|Argentina|Montserrat|Techtel LMDS Comunicaciones Interactivas S.A.|
|8|138.2.64.185|8118|Singapore|Singapore|Oracle Corporation|
|9|101.109.27.235|8080|Thailand|Bangkok|TOT Public Company Limited|
|10|159.192.249.10|8080|Thailand|Bangkok|CAT-BB|
|11|183.88.2.166|8080|Thailand|Ban Rae|Triple T Broadband Public Company Limited|
|12|5.195.40.27|8080|United Arab Emirates|Sharjah|Emirates Telecommunications Corporation|
|13|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|14|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|15|180.191.22.200|8080|Philippines|Cabanatuan City|Globe Telecom|
|16|103.19.130.50|8080|Bangladesh|Dhaka|InfoLink|
|17|14.207.144.82|8080|Thailand|Nakhon Pathom|Triple T Broadband Public Company Limited|
|18|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|19|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|20|176.192.70.58|8001|Russia|Moscow|Net By Net Holding LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


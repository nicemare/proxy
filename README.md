
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4577** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|203|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|203|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|203|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|610|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|413|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2303|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|134.122.85.174|8888|Germany|Frankfurt am Main|DigitalOcean, LLC|
|2|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|3|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|4|159.192.249.10|8080|Thailand|Bangkok|CAT-BB|
|5|89.58.10.16|3129|Germany|Nuremberg|netcup GmbH|
|6|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|37.32.22.223|80|Iran|Tehran|Noyan Abr Arvan Co. ( Private Joint Stock)|
|9|122.3.41.154|8090|Philippines|Manila|Philippine Long Distance Telephone Co.|
|10|181.37.179.186|999|Dominican Republic|Santo Domingo Este|Altice Dominicana S.A.|
|11|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|12|94.103.85.88|9300|Russia|Moscow|VDSINA|
|13|187.95.28.174|8080|Brazil|São José dos Campos|Netjacarei Telecon Ltda|
|14|87.247.186.105|80|Iran|Tehran|Insightometrics B.V.|
|15|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|16|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|17|103.183.119.160|3128|Vietnam|Tay Ho|MYCLOUD|
|18|103.163.134.247|9090|Indonesia|Plataran|PROVITEL|
|19|14.251.212.208|4004|Vietnam|Bac Ninh|VNPT|
|20|103.23.236.183|8080|India|Anupgarh|Kappa Internet Services Private Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


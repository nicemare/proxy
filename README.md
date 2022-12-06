
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5282** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|432|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|432|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|432|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|844|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|533|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2554|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|45.152.188.16|3128|United States|Ashburn|Sprint|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|5|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|6|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|7|45.152.188.16|3128|United States|Ashburn|Sprint|
|8|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|9|37.32.22.223|80|Iran|Tehran|Noyan Abr Arvan Co. ( Private Joint Stock)|
|10|176.10.97.97|8118|Switzerland|Zurich|Datasource AG|
|11|75.126.253.8|8080|United States|Dallas|SoftLayer|
|12|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|13|213.136.101.37|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|
|14|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|15|103.214.11.203|3128|Vietnam|Hanoi|MEGACORE|
|16|52.87.136.220|80|United States|Ashburn|Amazon.com, Inc.|
|17|103.214.11.197|3128|Vietnam|Hanoi|MEGACORE|
|18|177.82.85.209|3128|Brazil|Ribeirão Preto|Claro NXT Telecomunicacoes Ltda|
|19|51.79.50.22|9300|Canada|Victoria|OVH SAS|
|20|110.78.208.136|8080|Thailand|Chaiyo|CAT Telecom Public Company Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


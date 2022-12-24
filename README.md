
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5658** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|512|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|512|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|512|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1115|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|537|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2755|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|2|51.159.115.233|3128|France|Paris|SCALEWAY|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|212.112.113.178|3128|Kyrgyzstan|Bishkek|AkNet|
|5|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|6|181.129.14.163|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|7|185.218.126.155|39811|Germany|Düsseldorf|Contabo GmbH|
|8|130.185.225.240|3128|Bulgaria|Sofia|Telepoint Ltd|
|9|181.78.65.252|999|Colombia|Montería|IFX Networks Argentina S.R.L|
|10|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|201.151.239.190|999|Mexico|San Nicolás de los Garza|Alestra, S. de R.L. de C.V.|
|13|181.78.65.236|999|Colombia|Montería|IFX Networks Argentina S.R.L|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|16|82.208.23.113|3128|Germany|Düsseldorf|Casablanca INT|
|17|183.89.159.182|3128|Thailand|Pathum Thani|Triple T Broadband Public Company Limited|
|18|196.3.97.71|23500|Mozambique|Maputo|Eduardo Mondlane University|
|19|103.180.135.104|10006|Vietnam|Hanoi|Httvserver Technology Company Limited|
|20|210.245.124.131|5239|Vietnam|Ho Chi Minh City|FPT Telecom Company|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4507** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|180|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|180|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|180|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|555|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|294|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2407|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|181.129.14.164|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|167.250.47.187|8080|Brazil|Realeza|Inova Fibra|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|6|103.161.171.192|10000|Vietnam|Hanoi|VINABISON|
|7|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|8|103.161.171.113|10000|Vietnam|Hanoi|VINABISON|
|9|103.160.3.149|10000|Vietnam|Hanoi|ITEXPERT Viet Nam Joint Stock Company|
|10|103.161.171.202|10000|Vietnam|Hanoi|VINABISON|
|11|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|12|46.101.13.77|80|United Kingdom|London|DigitalOcean, LLC|
|13|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|14|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|15|134.238.252.143|8080|India|Mumbai|Google LLC|
|16|181.78.21.43|999|Colombia|Barrio San Luis|IFX Networks Argentina S.R.L|
|17|171.103.58.122|8080|Thailand|Bangkok|True Internet Co., Ltd.|
|18|46.39.241.205|8080|Russia|Moscow|RU.SU29 network|
|19|157.100.12.138|999|Ecuador|Alamor|Telconet S.A|
|20|45.167.125.97|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


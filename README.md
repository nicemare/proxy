
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5178** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|403|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|403|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|403|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|947|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|519|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2461|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|2|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|5|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|6|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|7|91.206.15.125|3128|Russia|Moscow|OOO "Network of data-centers "Selectel"|
|8|65.21.161.114|42069|Finland|Helsinki|Hetzner Online GmbH|
|9|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|1.53.252.228|2022|Vietnam|Ho Chi Minh City|FPT Telecom Company|
|12|203.150.128.146|8080|Thailand|Watthana|Internet Thailand Company Ltd|
|13|103.16.214.219|10000|Vietnam|Hanoi|TEK|
|14|103.16.215.10|10000|Vietnam|Hanoi|Httvserver Technology Company Limited|
|15|103.180.134.214|10006|Vietnam|Hanoi|Httvserver Technology Company Limited|
|16|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|17|94.127.219.99|8080|Russia|Moscow|ISP-company COMPLAT|
|18|45.177.55.102|999|Dominican Republic|Santiago de los Caballeros|Ingenieria EN Servicios De Telecomunicaciones Agml SRL|
|19|13.57.50.68|3128|United States|San Jose|Amazon.com, Inc.|
|20|158.255.215.50|9090|France|Saint-Mande|M247 Europe SRL|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


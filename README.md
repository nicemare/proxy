
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5241** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|410|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|410|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|410|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|970|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|525|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2495|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|2|34.82.107.67|80|United States|The Dalles|Google LLC|
|3|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|4|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|7|139.28.37.94|8080|Ukraine|Kyiv|Zemlyaniy Dmitro Leonidovich|
|8|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|9|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|10|34.82.107.67|80|United States|The Dalles|Google LLC|
|11|181.215.178.58|1337|Netherlands|Amsterdam|NovoServe B.V.|
|12|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|13|213.136.101.40|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|16|139.59.59.122|8118|India|Bengaluru|DIGITALOCEAN|
|17|148.251.150.106|3128|Germany|Falkenstein|Hetzner Online GmbH|
|18|223.205.76.23|8080|Thailand|Bang Lamung|Triple T Broadband Public Company Limited|
|19|193.122.134.214|80|United States|Ashburn|Oracle Corporation|
|20|204.185.204.64|8080|United States|Kansas City|org-morenet.more.net|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


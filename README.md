
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5701** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|500|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|500|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|500|

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
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|665|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2670|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|3|66.42.53.233|8000|Singapore|Singapore|The Constant Company|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|47.244.2.19|3128|Hong Kong|Central|Alibaba.com LLC|
|6|148.251.150.106|3128|Germany|Falkenstein|Hetzner Online GmbH|
|7|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|8|212.46.230.102|6969|Russia|Moscow|PJSC "Vimpelcom"|
|9|187.216.90.46|53281|Mexico|Cabo San Lucas|Uninet S.A. de C.V.|
|10|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|11|181.129.70.82|46752|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|12|43.243.142.60|59916|Indonesia|Tangerang|PT. Mora Telematika Indonesia|
|13|3.94.120.244|9812|United States|Ashburn|Amazon Technologies Inc.|
|14|181.143.106.162|52151|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|15|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|16|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|17|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|18|138.124.180.188|3128|United States|Secaucus|MIRholding B.V.|
|19|158.255.215.50|9090|France|Saint-Mande|Edis France|
|20|149.62.177.106|5555|Spain|Alhaurin de la Torre|Avatel Telecom|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


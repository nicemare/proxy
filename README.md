
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4408** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|114|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|114|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|114|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|356|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|270|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2431|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|4|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|5|86.120.122.3|3128|Romania|Pipera|RCS & RDS|
|6|75.126.253.8|8080|United States|Dallas|SoftLayer|
|7|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|10|54.38.153.122|8888|Germany|Limburg an der Lahn|OVH SAS|
|11|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|12|154.19.187.251|3128|Japan|Tokyo|SICLOUD INFORMATION TECHNOLOGY (HONGKONG) CO., LIMITED|
|13|75.126.253.8|8080|United States|Dallas|SoftLayer|
|14|159.203.31.27|8118|Canada|Toronto|DigitalOcean, LLC|
|15|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|16|89.208.219.121|8080|Netherlands|Amsterdam|My.com B.V.|
|17|75.126.253.8|8080|United States|Dallas|SoftLayer|
|18|177.141.99.50|8080|Brazil|São Paulo|Claro NXT Telecomunicacoes Ltda|
|19|103.231.241.102|80|Philippines|Quezon City|De La Salle University|
|20|123.182.59.84|8089|China|Zhangjiakou|Chinanet|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


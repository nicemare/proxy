
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6867** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|409|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|409|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|409|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1557|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1034|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3025|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|3|185.81.98.17|3131|Netherlands|Naaldwijk|WorldStream B.V.|
|4|103.178.43.101|8181|Indonesia|Jakarta|PT Jaring Solusi Persada|
|5|147.139.173.19|3128|Indonesia|Jakarta|Alibaba.com LLC|
|6|128.90.146.158|8118|Belgium|Brussels|Powerhouse Management, Inc.|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|75.126.253.8|8080|United States|Dallas|SoftLayer|
|9|159.89.196.22|443|Singapore|Singapore|DigitalOcean, LLC|
|10|5.39.105.211|3128|France|Lyon|OVH SAS|
|11|61.19.109.236|8080|Thailand|Ratchathewi|CAT-ISP|
|12|51.159.115.233|3128|France|Paris|SCALEWAY|
|13|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|14|217.169.210.110|8080|Serbia|Semlin|Orion Telekom Network|
|15|203.150.128.236|8080|Thailand|Watthana|Internet Thailand Company Ltd|
|16|185.200.36.165|8888|Turkey|Antakya|High Speed Telekomunikasyon ve Hab. Hiz. Ltd. Sti.|
|17|80.106.247.145|53410|Greece|Piraeus|Ote SA (Hellenic Telecommunications Organisation)|
|18|101.109.54.75|8080|Thailand|Si Racha|TOT Public Company Limited|
|19|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|20|192.155.95.228|10801|United States|Atlanta|Linode, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5030** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|169|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|169|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|169|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|926|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|396|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2457|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|5.78.41.22|3128|United States|Portland|Hetzner Online GmbH|
|3|45.152.188.248|3128|United States|Ashburn|Sprint|
|4|45.152.188.248|3128|United States|Ashburn|Sprint|
|5|52.45.139.115|80|United States|Ashburn|Amazon.com, Inc.|
|6|172.81.60.161|3128|United States|Phoenix|Dynu Systems Incorporated|
|7|172.81.60.161|3128|United States|Phoenix|Dynu Systems Incorporated|
|8|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|9|185.81.98.16|3131|Netherlands|Naaldwijk|WorldStream B.V.|
|10|151.49.244.114|3128|Italy|Roncade|INFOSTRADA|
|11|134.238.252.143|8080|India|Mumbai|Google LLC|
|12|139.180.189.22|3128|Singapore|Singapore|The Constant Company|
|13|217.67.190.154|3128|Russia|Moscow|Mastertel ISP|
|14|114.32.39.12|8080|Taiwan|Yangmei District|Chunghwa Telecom Co., Ltd.|
|15|164.92.248.2|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|16|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|17|131.72.68.161|40033|Brazil|Aracaju|TOP NET SERVIÇOS LTDA|
|18|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|19|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|20|185.8.165.134|8800|Czechia|Prague|Master Internet s.r.o.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


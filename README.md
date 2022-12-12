
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5040** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|314|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|314|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|314|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|865|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|357|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2567|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|51.159.115.233|3128|France|Paris|SCALEWAY|
|2|157.230.209.225|3128|United States|North Bergen|DigitalOcean, LLC|
|3|52.45.139.115|80|United States|Ashburn|Amazon.com, Inc.|
|4|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|5|157.230.209.225|3128|United States|North Bergen|DigitalOcean, LLC|
|6|52.45.139.115|80|United States|Ashburn|Amazon.com, Inc.|
|7|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|8|172.81.60.161|3128|United States|Phoenix|Dynu Systems Incorporated|
|9|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|181.215.178.67|1337|Netherlands|Amsterdam|NovoServe B.V.|
|12|157.100.55.143|999|Ecuador|Guayaquil|Nedetel S.A.|
|13|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|14|181.215.178.59|1337|Netherlands|Amsterdam|NovoServe B.V.|
|15|172.105.216.60|443|Japan|Tokyo|Linode, LLC|
|16|147.139.188.217|3128|Indonesia|Jakarta|Alibaba.com LLC|
|17|103.130.4.17|8080|Indonesia|Samarinda|LINTASMAYA|
|18|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|19|37.120.192.154|8080|Netherlands|Amsterdam|M247 Europe SRL|
|20|154.85.55.174|3128|United States|Los Angeles|Beijing Baidu Netcom Science and Technology Co., Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


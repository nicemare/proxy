
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6012** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|501|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|501|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|501|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1138|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|898|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2725|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|2|135.148.95.28|3128|United States|Reston|OVH SAS|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|6|173.47.77.210|80|United States|Boise|Cable ONE|
|7|181.78.65.252|999|Colombia|Montería|IFX Networks Argentina S.R.L|
|8|146.56.118.144|7890|South Korea|Chuncheon|Oracle Corporation|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|75.126.253.8|8080|United States|Dallas|SoftLayer|
|11|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|12|103.141.108.122|8080|Indonesia|Blitar|Data Buana Nusantara|
|13|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|14|135.148.95.28|3128|United States|Reston|OVH SAS|
|15|70.177.15.10|8080|United States|Gilbert|Cox Communications Inc.|
|16|103.148.209.141|8282|Indonesia|Sukoharjo|Dinas Komunikasi Informatika DAN Statistik Kota Blitar|
|17|105.174.7.254|8080|Angola|Luanda|UNITEL SA|
|18|192.155.95.228|10801|United States|Atlanta|Linode, LLC|
|19|179.152.30.38|8080|Brazil|Viamão|Claro NXT Telecomunicacoes Ltda|
|20|119.76.142.242|8080|Thailand|Nakhon Ratchasima|True Internet Co., Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


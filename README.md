
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5323** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|509|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|509|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|509|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1003|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|663|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2306|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|49.51.90.57|3128|Canada|Barrie|OPHL|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|4|75.126.253.8|8080|United States|Dallas|SoftLayer|
|5|45.152.188.16|3128|United States|Ashburn|Sprint|
|6|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|7|116.203.202.160|8443|Germany|Nuremberg|Hetzner Online GmbH|
|8|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|9|51.159.115.233|3128|France|Paris|SCALEWAY|
|10|75.126.253.8|8080|United States|Dallas|SoftLayer|
|11|45.152.188.16|3128|United States|Ashburn|Sprint|
|12|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|13|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|14|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|15|134.238.252.143|8080|India|Mumbai|Google LLC|
|16|88.135.130.183|3128|Latvia|Riga|Telenet SIA|
|17|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|18|51.79.50.22|9300|Canada|Victoria|OVH SAS|
|19|190.2.210.237|999|Colombia|Pasto|TV AZTECA SUCURSAL COLOMBIA|
|20|93.177.73.122|8888|Germany|Frankfurt am Main|M247 Europe SRL|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


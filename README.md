
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5169** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|495|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|495|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|495|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|907|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|478|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2501|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|170.39.194.16|3128|United States|Ashburn|Rackdog, LLC|
|2|149.202.160.140|8090|France|Gravelines|OVH SAS|
|3|20.229.33.75|8080|Netherlands|Amsterdam|Microsoft Corporation|
|4|92.205.22.114|38080|France|Strasbourg|GD MASS Network|
|5|170.39.194.16|3128|United States|Ashburn|Rackdog, LLC|
|6|51.159.115.233|3128|France|Paris|SCALEWAY|
|7|181.215.178.39|1337|Netherlands|Amsterdam|NovoServe B.V.|
|8|20.234.198.245|8080|Netherlands|Amsterdam|Microsoft Corporation|
|9|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|10|172.104.60.117|3128|Singapore|Singapore|Linode, LLC|
|11|138.68.97.216|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|12|80.249.187.85|8080|Russia|St Petersburg|Smart Telecom Company|
|13|38.54.85.165|4780|Hong Kong|Hong Kong|Kaopu Cloud HK Limited|
|14|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|15|181.48.107.26|999|Colombia|Bogotá|Telmex Colombia S.A.|
|16|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|17|168.228.49.161|8080|Costa Rica|San Ramon|Cooperativa de Electrificación Rural de San Carlos R.L. (Coopelesca R.L.)|
|18|103.17.182.14|9191|Indonesia|Bandung|PT Tinelo Digital Network|
|19|118.42.15.57|4007|South Korea|Seongnam-si|Korea Telecom|
|20|112.140.186.124|808|Singapore|Singapore|Sparkstation Pte Ltd|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


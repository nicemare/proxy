
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6408** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|680|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|680|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|680|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1398|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1034|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3025|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|23.95.186.182|3128|United States|Washington|ColoCrossing|
|2|20.121.184.238|443|United States|Boydton|Microsoft Corporation|
|3|135.148.95.28|3128|United States|Reston|OVH SAS|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|135.148.95.28|3128|United States|Reston|OVH SAS|
|6|190.45.251.189|3128|Chile|Santiago|VTR BANDA ANCHA S.A.|
|7|168.138.211.5|8080|Japan|Tokyo|Oracle Corporation|
|8|190.63.35.30|9812|Ecuador|Ambato|CONECEL|
|9|182.52.137.140|8080|Thailand|Khwaeng Thung Song Hong|TOT Public Company Limited|
|10|88.1.165.183|3128|Spain|Tarancon|Telefonica de Espana SAU|
|11|191.103.219.225|48612|Colombia|Montería|Edatel S.a. E.S.P|
|12|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|13|140.227.61.156|23456|Japan|Chiyoda-ku|InfoSphere|
|14|103.155.197.36|8080|Indonesia|Sukabumi|JEMBATANDATA|
|15|103.175.46.23|3125|Indonesia|Cirebon|PT Internet Keluarga Indonesia|
|16|102.130.192.231|8080|Angola|Luanda|Finstar - Sociedade de Investimento e Participacoes S.A|
|17|113.53.53.7|8080|Thailand|Lopburi|TOT Public Company Limited|
|18|85.94.81.194|8080|Croatia|Zagreb|Terrakom d.o.o.|
|19|206.189.154.106|443|Singapore|Singapore|DigitalOcean, LLC|
|20|45.174.168.10|999|Mexico|Tulancingo|Wiiki Networks S De R.l. De C.V.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


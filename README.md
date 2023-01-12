
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
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|487|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|487|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|487|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1252|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|947|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2858|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|3|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|4|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|5|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|6|157.230.241.229|443|Singapore|Singapore|DigitalOcean, LLC|
|7|45.174.168.4|999|Mexico|Tulancingo|Wiiki Networks S De R.l. De C.V.|
|8|12.144.254.185|9080|United States|Little Rock|AT&T Services, Inc.|
|9|45.174.168.8|999|Mexico|Tulancingo|Wiiki Networks S De R.l. De C.V.|
|10|207.188.11.31|80|United States|San Antonio|H5 Data Centers - Chandler LLC|
|11|188.133.158.145|8080|Russia|Moscow|Enforta-MSK|
|12|60.164.247.52|9002|China|Yuzhong Chengguanzhen|China Telecom|
|13|50.201.51.216|8080|United States|Pittsburgh|Comcast Cable Communications, LLC|
|14|179.49.117.226|999|Honduras|La Galera|Asociacion De Servicio De Internet S. De RL|
|15|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|16|79.122.202.20|8080|Russia|Moscow|Enforta-TMN|
|17|103.151.30.81|8080|Bangladesh|Tongi|Bright Star Network|
|18|46.191.235.167|443|Russia|Ufa|JSC "Ufanet"|
|19|179.43.96.178|8080|Peru|Arequipa|GLG PERU SAC|
|20|219.148.43.102|3128|China|Beijing|Chinanet|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


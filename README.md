
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6128** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|352|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|352|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|352|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1198|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|978|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2569|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|3|18.209.97.228|3128|United States|Ashburn|Amazon.com, Inc.|
|4|137.184.72.54|80|United States|North Bergen|DigitalOcean, LLC|
|5|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|6|34.172.161.155|3128|United States|Council Bluffs|Google LLC|
|7|94.103.85.88|9300|Russia|Moscow|VDSINA|
|8|187.72.232.218|3128|Brazil|Itumbiara|ALGAR TELECOM S/A|
|9|137.184.224.26|3128|United States|Santa Clara|DigitalOcean, LLC|
|10|186.96.148.144|999|Mexico|Mexico City|Total Play Telecomunicaciones SA De CV|
|11|122.155.165.191|3128|Thailand|Ratchathewi|CAT Telecom Public Company Limited|
|12|101.226.17.188|9002|China|Shanghai|China Telecom (Group)|
|13|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|14|219.148.43.102|3128|China|Beijing|Chinanet|
|15|111.225.152.114|8089|China|Gaocheng|Chinanet|
|16|111.225.152.109|8089|China|Gaocheng|Chinanet|
|17|186.136.56.77|3128|Argentina|Mar del Plata|Telecom Argentina S.A|
|18|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|19|109.228.64.226|81|Montenegro|Berane|Crnogorski Telekom A.D. Podgorica|
|20|185.190.38.150|8080|Kosovo|Dubova|Kadri Haxhiaj trading as "B.I."|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


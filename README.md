
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5353** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|422|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|422|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|422|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1045|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|479|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2446|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|52.86.238.141|3128|United States|Ashburn|Amazon.com, Inc.|
|2|52.86.238.141|3128|United States|Ashburn|Amazon.com, Inc.|
|3|178.32.116.64|3128|France|Roubaix|OVH SAS|
|4|95.217.120.82|3368|Finland|Helsinki|Hetzner Online GmbH|
|5|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|6|15.168.32.52|3128|Japan|Osaka|Amazon Technologies Inc.|
|7|54.37.242.65|3128|United Kingdom|London|OVH SAS|
|8|94.45.137.34|8080|Ukraine|Kyiv Oblast|Kievline LLC|
|9|145.40.121.73|3128|Brazil|São Paulo|Packet Host, Inc.|
|10|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|11|218.32.248.8|3128|Taiwan|New Taipei|New Centry InfoComm Tech. Co., Ltd.|
|12|188.6.133.183|8080|Hungary|Szazhalombatta|Magyar Telekom|
|13|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|14|117.251.103.186|8080|India|Hazratpur|BSNL Internet|
|15|187.130.139.197|8080|Mexico|Mexico City|Uninet S.A. de C.V.|
|16|117.240.53.116|3128|India|Bengaluru|BSNL Internet|
|17|114.7.27.98|8080|Indonesia|Jakarta|PT. INDOSAT Tbk|
|18|122.49.208.230|3128|Philippines|San Juan|WifiCity, Inc|
|19|193.141.65.48|808|Iran|Tehran|Green Web Samaneh Novin Co Ltd|
|20|196.223.63.234|8080|South Africa|Pretoria|Telemasters|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


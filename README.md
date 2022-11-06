
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5248** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|659|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|659|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|659|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|997|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|605|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2563|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|204.185.204.64|8080|United States|Kansas City|org-morenet.more.net|
|2|178.32.116.64|3128|France|Roubaix|OVH SAS|
|3|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|204.185.204.64|8080|United States|Kansas City|org-morenet.more.net|
|5|117.251.103.186|8080|India|Hazratpur|BSNL Internet|
|6|191.249.72.144|80|Brazil|Palhoca|TELEFÔNICA BRASIL S.A|
|7|122.49.208.230|3128|Philippines|San Juan|WifiCity, Inc|
|8|194.8.218.100|8080|Germany|Aachen|NetCologne Gesellschaft fur Telekommunikation mbH|
|9|103.183.60.226|9812|Indonesia|Jakarta|LINTASARTA|
|10|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|11|193.141.65.48|808|Iran|Tehran|Green Web Samaneh Novin Co Ltd|
|12|122.49.208.242|3128|Philippines|San Juan|WifiCity, Inc|
|13|208.180.105.70|8080|United States|Amarillo|Suddenlink Communications|
|14|85.14.243.31|3128|Germany|Kamp-Lintfort|myLoc managed IT AG|
|15|68.183.242.248|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|16|198.59.191.234|8080|United States|Las Cruces|TDS TELECOM|
|17|190.187.201.26|8080|Peru|Sechura|Americatel Peru S.A.|
|18|5.189.140.113|8118|Germany|Nuremberg|Contabo GmbH|
|19|117.102.70.42|8080|Indonesia|Bandung|BIZNET|
|20|45.167.125.97|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


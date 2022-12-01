
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4860** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|310|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|310|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|310|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|843|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|327|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2339|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|159.65.189.163|8080|United States|Clifton|DigitalOcean, LLC|
|4|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|7|181.78.10.10|999|Colombia|El Zarzal|IFX Networks Argentina S.R.L|
|8|159.65.189.163|8080|United States|Clifton|DigitalOcean, LLC|
|9|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|10|184.82.239.214|8080|Thailand|Bangkok|AIS-Fibre|
|11|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|12|27.79.0.22|10000|Vietnam|Buon Ma Thuot|Viettel Corporation|
|13|51.159.115.233|3128|France|Paris|SCALEWAY|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|119.42.71.29|53281|Thailand|Ban Sop Bua|CAT-BB|
|16|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|17|182.253.98.167|8080|Indonesia|Banjar Medura|BIZNET|
|18|110.34.3.229|3128|Nepal|Kathmandu|SUBISU C7|
|19|168.194.171.16|999|Peru|Lima|FASTNET|
|20|190.121.239.178|8080|Venezuela|San Juan de los Morros|Corporacion Digitel C.A|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


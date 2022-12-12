
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5009** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|340|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|340|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|340|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|823|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|443|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2492|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|2|98.114.196.64|8118|United States|Downingtown|Verizon Business|
|3|64.227.6.0|4003|United States|North Bergen|DigitalOcean, LLC|
|4|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|5|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|6|181.78.65.250|999|Colombia|Bogotá|IFX Networks Argentina S.R.L|
|7|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|10|145.40.121.15|3128|Brazil|São Paulo|Packet Host, Inc.|
|11|191.252.196.14|8888|Brazil|Itacoatiara|Locaweb Serviços de Internet S/A|
|12|145.40.121.157|3128|Brazil|São Paulo|Packet Host, Inc.|
|13|95.0.90.243|8080|Turkey|Istanbul|Turk Telekomunikasyon Anonim Sirketi|
|14|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|15|159.192.249.10|8080|Thailand|Bangkok|CAT-BB|
|16|140.227.25.191|23456|Japan|Yonabaru|InfoSphere|
|17|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|18|194.233.84.239|80|Singapore|Singapore|Contabo Asia Private Limited|
|19|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|20|116.111.173.12|4001|Vietnam|Hanoi|Viettel Corporation|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


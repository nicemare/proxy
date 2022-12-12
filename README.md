
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4743** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|338|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|338|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|338|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|738|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|384|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2370|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.152.188.248|3128|United States|Ashburn|Sprint|
|2|189.252.86.209|8080|Mexico|Ahome|Uninet S.A. de C.V.|
|3|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|82.99.194.30|3128|Iran|Khorramshahr|ParsOnline Co.|
|6|45.152.188.248|3128|United States|Ashburn|Sprint|
|7|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|8|145.40.121.157|3128|Brazil|São Paulo|Packet Host, Inc.|
|9|194.195.90.215|8118|Singapore|Singapore|Contabo Asia Private Limited|
|10|181.78.65.250|999|Colombia|Bogotá|IFX Networks Argentina S.R.L|
|11|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|12|103.141.247.6|8080|India|Palakkad|Vinayaga Communications Pvt Ltd|
|13|176.196.250.86|3128|Russia|Kemerovo|Goodline.info|
|14|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|15|209.141.54.136|5555|United States|Las Vegas|FranTech Solutions|
|16|181.78.65.238|999|Colombia|Bogotá|IFX Networks Argentina S.R.L|
|17|210.179.58.236|80|South Korea|Naju-si|Korea Telecom|
|18|159.89.132.167|8989|United States|Santa Clara|DigitalOcean, LLC|
|19|200.25.254.193|54240|Colombia|Puerto Carreño|Andinet ON Line|
|20|105.112.191.250|3128|Nigeria|Lagos|Airtel Networks Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


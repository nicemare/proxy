
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5259** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|424|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|424|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|424|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1069|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|564|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2675|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|149.56.233.29|3128|Canada|Montreal|OVH Hosting|
|2|51.159.115.233|3128|France|Paris|SCALEWAY|
|3|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|6|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|7|159.192.249.10|8080|Thailand|Bangkok|CAT-BB|
|8|68.183.185.62|80|Singapore|Singapore|DigitalOcean, LLC|
|9|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|10|194.195.90.215|8118|Singapore|Singapore|Contabo Asia Private Limited|
|11|171.227.71.224|4002|Vietnam|Ho Chi Minh City|Viettel Corporation|
|12|64.227.23.88|8118|United States|North Bergen|DigitalOcean, LLC|
|13|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|14|158.69.71.245|9300|Canada|Montreal|OVH SAS|
|15|5.160.179.8|8080|Iran|Tehran|Respina Networks & Beyond PJSC|
|16|181.78.27.38|999|Paraguay|Asunción|Ufinet Paraguay S.A|
|17|186.96.101.76|999|Colombia|Bogotá|TV AZTECA SUCURSAL COLOMBIA|
|18|134.122.58.174|80|Netherlands|Amsterdam|DigitalOcean, LLC|
|19|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|20|161.132.125.244|8080|Peru|Lima|Optical Technologies S.A.C.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


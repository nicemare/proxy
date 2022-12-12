
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5088** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|429|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|429|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|429|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|949|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|431|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2457|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|45.152.188.248|3128|United States|Ashburn|Sprint|
|2|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|3|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|4|45.152.188.248|3128|United States|Ashburn|Sprint|
|5|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|6|165.192.111.151|3129|United States|Seattle|SoftLayer|
|7|165.192.111.151|3129|United States|Seattle|SoftLayer|
|8|37.32.22.223|80|Iran|Tehran|Noyan Abr Arvan Co. ( Private Joint Stock)|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|87.247.186.105|80|Iran|Tehran|Insightometrics B.V.|
|11|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|12|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|13|113.23.176.254|8118|Malaysia|Ipoh|Extreme Broadband|
|14|1.53.252.228|2022|Vietnam|Ho Chi Minh City|FPT Telecom Company|
|15|45.70.6.199|8080|Brazil|Serra Talhada|OLITECH INFORMÁTICA E COMUNICAÇÃO LTDA|
|16|125.25.33.115|8080|Thailand|Chiang Mai|TOT Public Company Limited|
|17|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|18|194.233.84.239|80|Singapore|Singapore|Contabo Asia Private Limited|
|19|200.25.254.193|54240|Colombia|Puerto Carreño|Andinet ON Line|
|20|119.76.142.238|8080|Thailand|Nakhon Ratchasima|True Internet Co., Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


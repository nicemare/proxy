
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4754** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|303|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|303|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|303|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|724|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|428|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2351|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|51.222.75.219|8080|Canada|Beauharnois|OVH Hosting|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|6|86.120.122.3|3128|Romania|Pipera|RCS & RDS|
|7|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|8|188.132.222.11|8080|Turkey|Skutari|High Speed Telekomunikasyon ve Hab. Hiz. Ltd. Sti.|
|9|158.69.72.138|9300|Canada|Montreal|OVH SAS|
|10|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|11|154.85.55.174|3128|United States|Los Angeles|Beijing Baidu Netcom Science and Technology Co., Ltd.|
|12|45.152.188.16|3128|United States|Ashburn|Sprint|
|13|46.246.6.5|8118|Sweden|Stockholm|Portlane Network|
|14|114.32.39.12|8080|Taiwan|Yangmei District|Chunghwa Telecom Co., Ltd.|
|15|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|16|174.138.116.12|80|United States|Clifton|DigitalOcean, LLC|
|17|80.84.176.110|8080|Ukraine|Zaporizhzhya|Express Radio Networks|
|18|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|19|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|20|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


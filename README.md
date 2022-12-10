
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4730** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|226|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|226|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|226|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|655|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|368|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2456|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|64.225.8.192|80|United States|Clifton|DigitalOcean, LLC|
|2|157.245.222.183|80|United States|Clifton|DigitalOcean, LLC|
|3|139.28.37.94|8080|Ukraine|Kyiv|Zemlyaniy Dmitro Leonidovich|
|4|134.238.252.143|8080|India|Mumbai|Google LLC|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|37.32.22.223|80|Iran|Tehran|Noyan Abr Arvan Co. ( Private Joint Stock)|
|7|34.82.107.67|80|United States|The Dalles|Google LLC|
|8|101.109.103.168|8080|Thailand|Tha Takiap|TOT Public Company Limited|
|9|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|10|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|11|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|12|160.16.130.191|3128|Japan|Tokyo|SAKURA Internet Inc.|
|13|172.105.216.60|443|Japan|Tokyo|Linode, LLC|
|14|75.126.253.8|8080|United States|Dallas|SoftLayer|
|15|27.77.245.210|4013|Vietnam|Ho Chi Minh City|Newass2011xDSLHCMC|
|16|164.92.76.73|30022|United States|Santa Clara|DigitalOcean, LLC|
|17|4.246.220.253|8080|United States|Boydton|Microsoft Corporation|
|18|173.219.112.85|8080|United States|Chicago|Suddenlink Communications|
|19|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|20|20.121.41.148|9999|United States|Boydton|Microsoft Corporation|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


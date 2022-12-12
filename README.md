
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4382** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|209|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|209|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|209|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|708|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|331|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2392|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|134.238.252.143|8080|India|Mumbai|Google LLC|
|4|89.85.119.151|8118|France|Lens|Bouygues Telecom ISP|
|5|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|6|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|7|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|8|36.90.90.223|8080|Indonesia|Karangampel|PT. Telekomunikasi Indonesia|
|9|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|10|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|11|157.245.207.186|8080|United States|Tooele|DigitalOcean, LLC|
|12|70.177.15.10|8080|United States|Gilbert|Cox Communications Inc.|
|13|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|14|191.97.1.89|999|Colombia|El Dovio|TV AZTECA SUCURSAL COLOMBIA|
|15|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|16|178.128.156.76|3128|United States|North Bergen|DigitalOcean, LLC|
|17|185.248.12.38|9090|Turkey|Istanbul|AtlantisTelekom|
|18|112.87.140.163|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|19|182.253.109.41|8080|Indonesia|Semarang|Biznet Metronet|
|20|195.154.255.194|8000|France|Bouglainval|Online S.A.S.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5400** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|408|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|408|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|408|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|983|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|501|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2665|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|4.246.220.253|8080|United States|Boydton|Microsoft Corporation|
|2|45.152.188.16|3128|United States|Ashburn|Sprint|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|89.85.119.151|8118|France|Lens|Bouygues Telecom ISP|
|5|88.80.226.36|3128|Slovakia|Nitra|SATRO s.r.o.|
|6|190.162.91.197|3128|Chile|La Florida|VTR BANDA ANCHA S.A.|
|7|142.132.207.106|3128|Germany|Falkenstein|Hetzner Online GmbH|
|8|37.187.20.166|3128|France|Roubaix|OVH SAS|
|9|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|10|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|11|75.126.253.8|8080|United States|Dallas|SoftLayer|
|12|74.91.116.171|3128|United States|New York|Internap Holding LLC|
|13|70.44.204.206|8888|United States|Reading|PenTeleData Inc.|
|14|167.71.190.253|80|United States|Clifton|DigitalOcean, LLC|
|15|45.152.188.16|3128|United States|Ashburn|Sprint|
|16|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|
|17|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|18|210.212.129.109|9001|India|Surat|BSNL Internet|
|19|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|20|4.246.220.253|8080|United States|Boydton|Microsoft Corporation|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


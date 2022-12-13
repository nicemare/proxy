
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5098** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|397|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|397|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|397|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|0|🚫|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1040|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|575|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2547|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|137.184.93.221|8080|United States|Santa Clara|DigitalOcean, LLC|
|3|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|4|8.29.103.131|8080|United States|Dawsonville|North Georgia Network Cooperative, Inc|
|5|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|6|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|7|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|8|134.238.252.143|8080|India|Mumbai|Google LLC|
|9|8.29.103.131|8080|United States|Dawsonville|North Georgia Network Cooperative, Inc|
|10|103.175.46.9|3125|Indonesia|Cirebon|PT Internet Keluarga Indonesia|
|11|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|12|75.126.253.8|8080|United States|Dallas|SoftLayer|
|13|173.82.153.196|16781|United States|Portland|Multacom Corporation|
|14|87.247.186.105|80|Iran|Tehran|Insightometrics B.V.|
|15|3.208.195.132|3128|United States|Ashburn|Amazon Technologies Inc.|
|16|137.184.93.221|8080|United States|Santa Clara|DigitalOcean, LLC|
|17|142.129.238.249|80|United States|Pomona|Charter Communications Inc|
|18|152.44.42.188|5566|United States|Bloomington|UpCloud USA Inc|
|19|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|20|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


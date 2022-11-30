
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5222** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|359|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|359|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|359|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|853|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|591|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2527|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|5|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|6|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|90.166.42.65|1234|Spain|Torre Pacheco|Uni2|
|9|43.135.156.130|59394|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|10|155.4.244.218|80|Sweden|Stockholm|Bahnhof AB|
|11|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|12|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|
|13|43.135.156.130|59394|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|14|103.152.232.122|3125|Indonesia|Subang|PT Kingpolah Network Solutions|
|15|185.237.99.218|61443|United Kingdom|London|Kamatera Inc|
|16|168.119.175.224|3128|Germany|Nuremberg|Hetzner Online GmbH|
|17|161.53.129.23|3128|Croatia|Krapinske Toplice|Croatian Academic and Research Network|
|18|74.82.50.155|3128|Japan|Shinagawa|Hurricane Electric|
|19|51.79.152.70|3128|Singapore|Singapore|OVH SAS|
|20|182.90.224.115|3128|China|Beihai|China Unicom Guangxi Province Network|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


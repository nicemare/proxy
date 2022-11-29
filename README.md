
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5005** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|420|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|420|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|420|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1076|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|390|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2288|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|190.113.41.163|999|Dominican Republic|Santo Domingo Este|MR Networking, SRL|
|3|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|4|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|5|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|6|75.126.253.8|8080|United States|Dallas|SoftLayer|
|7|45.174.77.243|999|Mexico|Chihuahua City|Raul Duarte Urita|
|8|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|11|130.185.73.47|808|Iran|Tehran|Pars Parva System Ltd|
|12|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|13|155.4.244.218|80|Sweden|Stockholm|Bahnhof AB|
|14|103.151.30.90|8080|Bangladesh|Tongi|Bright Star Network|
|15|181.48.107.26|999|Colombia|Bogotá|Telmex Colombia S.A.|
|16|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|17|158.51.107.253|8080|United States|Fredericksburg|4 ip Technology and Media, LLC|
|18|2.180.33.41|3128|Iran|Mashhad|mashhad|
|19|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|20|113.53.47.150|8080|Thailand|Ban Kho|TOT Public Company Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


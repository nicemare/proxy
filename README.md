
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5051** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|414|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|414|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|414|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|935|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|577|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2288|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|13.57.130.106|8080|United States|San Jose|Amazon.com, Inc.|
|2|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|13.57.130.106|8080|United States|San Jose|Amazon.com, Inc.|
|5|134.238.252.143|8080|India|Mumbai|Google LLC|
|6|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|7|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|8|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|9|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|10|130.185.73.47|808|Iran|Tehran|Pars Parva System Ltd|
|11|177.93.52.82|999|Colombia|Bogotá|TV AZTECA SUCURSAL COLOMBIA|
|12|52.87.136.220|80|United States|Ashburn|Amazon.com, Inc.|
|13|5.9.152.185|80|Germany|Falkenstein|Hetzner Online GmbH|
|14|167.71.212.129|35111|Singapore|Singapore|DigitalOcean, LLC|
|15|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|
|16|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|17|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|18|182.253.153.42|8080|Indonesia|Jakarta|BIZNET|
|19|117.103.163.12|8080|Japan|Toshima|NTT PC Communications, Inc.|
|20|20.175.131.102|3128|Canada|Toronto|Microsoft Corporation|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


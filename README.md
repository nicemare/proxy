
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4622** proxies at the latest update. Usable proxies are below.

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|726|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|214|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2431|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|49.51.90.57|3128|Canada|Barrie|OPHL|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|75.126.253.8|8080|United States|Dallas|SoftLayer|
|5|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|6|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|7|18.235.55.193|8080|United States|Ashburn|Amazon.com, Inc.|
|8|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|9|116.203.202.160|8443|Germany|Nuremberg|Hetzner Online GmbH|
|10|45.152.188.16|3128|United States|Ashburn|Sprint|
|11|134.238.252.143|8080|India|Mumbai|Google LLC|
|12|83.170.219.86|8081|Ukraine|Kyiv|Golden Telecom Network|
|13|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|14|213.136.101.40|3128|Ivory Coast|Abidjan|ORANGE COTE D'IVOIRE|
|15|45.152.188.16|3128|United States|Ashburn|Sprint|
|16|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|17|143.244.133.78|80|India|Bengaluru|DigitalOcean, LLC|
|18|170.80.202.241|999|Dominican Republic|Santiago de los Caballeros|RUDDY GONZALEZ DIGITAL MEDIA DOMINICANA, RGDIMAX, S.R.L|
|19|69.75.140.157|8080|United States|San Luis|Spectrum|
|20|45.167.125.97|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


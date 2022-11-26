
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4272** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|199|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|199|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|199|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|431|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|195|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2295|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|170.39.116.114|3128|United States|Ashburn|Rackdog, LLC|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|192.99.34.64|1337|Canada|Beauharnois|OVH SAS|
|4|35.79.37.45|80|Japan|Tokyo|Amazon.com, Inc.|
|5|43.206.81.172|80|Japan|Tokyo|Amazon.com, Inc.|
|6|170.39.118.22|3128|United States|Ashburn|Rackdog, LLC|
|7|141.94.137.176|1337|France|Gravelines|OVH SAS|
|8|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|9|206.189.37.48|8080|Singapore|Singapore|DigitalOcean, LLC|
|10|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|11|170.39.116.114|3128|United States|Ashburn|Rackdog, LLC|
|12|75.126.253.8|8080|United States|Dallas|SoftLayer|
|13|134.238.252.143|8080|India|Mumbai|Google LLC|
|14|170.39.118.22|3128|United States|Ashburn|Rackdog, LLC|
|15|117.251.103.186|8080|India|Noida|BSNL Internet|
|16|43.135.156.130|59394|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|17|154.19.187.251|3128|Japan|Tokyo|SICLOUD INFORMATION TECHNOLOGY (HONGKONG) CO., LIMITED|
|18|133.242.171.216|3128|Japan|Chiyoda|SAKURA Internet Inc.|
|19|76.72.138.48|3128|United States|Easton|Easton Utilities Commission|
|20|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5500** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|422|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|422|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|422|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1264|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|300|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2585|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|208.82.61.12|3128|United States|Ashburn|Bernardi Sounds|
|3|45.152.188.16|3128|United States|Ashburn|Sprint|
|4|208.82.61.13|3128|United States|Ashburn|Bernardi Sounds|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|152.67.250.2|3129|United States|San Jose|Oracle Corporation|
|7|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|8|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|9|208.82.61.15|3128|United States|Ashburn|Bernardi Sounds|
|10|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|11|208.82.61.12|3128|United States|Ashburn|Bernardi Sounds|
|12|149.56.233.29|3128|Canada|Montreal|OVH Hosting|
|13|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|14|14.207.151.221|8080|Thailand|Nakhon Pathom|Triple T Broadband Public Company Limited|
|15|116.98.177.102|10000|Vietnam|Buon Ma Thuot|Viettel Corporation|
|16|75.126.253.8|8080|United States|Dallas|SoftLayer|
|17|119.8.236.97|3128|Hong Kong|Hong Kong|Huawei International Pte. Ltd.|
|18|45.152.188.16|3128|United States|Ashburn|Sprint|
|19|208.82.61.15|3128|United States|Ashburn|Bernardi Sounds|
|20|51.159.115.233|3128|France|Paris|SCALEWAY|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


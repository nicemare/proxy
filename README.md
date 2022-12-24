
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5364** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|216|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|216|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|216|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|722|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|636|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2755|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|2|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|3|212.112.113.178|3128|Kyrgyzstan|Bishkek|AkNet|
|4|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|5|158.69.71.245|9300|Canada|Montreal|OVH SAS|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|8|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|9|103.161.119.45|10016|Vietnam|Ho Chi Minh City|THIENCO|
|10|112.78.167.32|8080|Indonesia|Jakarta|Biznet Networks|
|11|14.97.155.42|3128|India|Delhi|Tata Teleservices LTD - Tata Indicom - Cdma Division|
|12|103.178.232.223|10006|Vietnam|Da Nang|Viet Digital Technology Liability Company|
|13|103.16.224.134|10001|Vietnam|Hanoi|ATH|
|14|51.79.50.22|9300|Canada|Beauharnois|OVH SAS|
|15|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|16|144.217.119.85|3207|Canada|Beauharnois|OVH Hosting|
|17|140.227.61.156|23456|Japan|Chiyoda|InfoSphere|
|18|161.35.223.141|80|Germany|Frankfurt am Main|DigitalOcean, LLC|
|19|138.121.55.241|8080|Brazil|Raul Soares|Signet Telecom Ltda|
|20|195.154.255.194|8000|France|Vitry-sur-Seine|Online S.A.S.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


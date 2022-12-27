
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5600** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|368|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|368|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|368|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1063|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|540|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2746|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|142.4.215.171|3128|Canada|Beauharnois|OVH SAS|
|2|152.228.206.188|80|France|Roubaix|OVH SAS|
|3|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|4|18.159.181.93|8088|Germany|Frankfurt am Main|Amazon.com, Inc.|
|5|47.254.156.107|8000|Germany|Frankfurt am Main|Alibaba.com LLC|
|6|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|7|186.251.123.100|8080|Brazil|Sertanopolis|N G B Pires & CIA LTDA|
|8|138.2.8.164|8000|Japan|Tokyo|Oracle Corporation|
|9|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|103.10.68.104|10022|Vietnam|Hanoi|HVC|
|13|110.78.208.91|8000|Thailand|Ratchathewi|CAT Telecom Public Company Limited|
|14|103.16.214.109|10002|Vietnam|Hanoi|TEK|
|15|103.16.215.162|10014|Vietnam|Hanoi|Httvserver Technology Company Limited|
|16|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|17|103.16.160.36|10006|Vietnam|Chúc Sơn|ANH|
|18|58.27.253.68|8080|Pakistan|Karachi|Wateen Telecom Limited|
|19|103.16.224.142|10000|Vietnam|Hanoi|ATH|
|20|107.172.73.179|7890|Canada|Hamilton|ColoCrossing|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


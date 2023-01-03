
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5509** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|418|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|418|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|418|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1126|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|644|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2388|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|2|34.84.72.91|3128|Japan|Tokyo|Google LLC|
|3|139.59.241.101|443|Singapore|Singapore|DigitalOcean, LLC|
|4|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|5|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|6|143.198.182.218|80|United States|North Bergen|DigitalOcean, LLC|
|7|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|8|69.75.140.157|8080|United States|San Luis|Spectrum|
|9|4.246.220.253|8080|United States|Boydton|Microsoft Corporation|
|10|110.78.208.91|8080|Thailand|Ratchathewi|CAT Telecom Public Company Limited|
|11|51.79.50.22|9300|Canada|Beauharnois|OVH SAS|
|12|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|13|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|14|23.95.186.182|3128|United States|Washington|ColoCrossing|
|15|128.199.55.6|443|Netherlands|Amsterdam|DigitalOcean, LLC|
|16|134.238.252.143|8080|India|Mumbai|Google LLC|
|17|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|18|96.68.234.217|8080|United States|Springfield|Comcast Cable Communications, LLC|
|19|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|20|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


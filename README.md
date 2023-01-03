
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5243** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|182|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|182|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|182|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|22|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1213|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|495|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2562|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|201.76.184.66|8080|Brazil|Rio de Janeiro|Mundivox Do Brasil Ltda|
|3|112.87.140.164|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|4|187.17.228.98|3128|Brazil|Louveira|Lantec Comunicacao Multimidia Ltda|
|5|112.87.140.164|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|6|41.215.4.242|8080|Kenya|Nairobi|Accesskenya Group LTD Network|
|7|79.172.212.99|3128|Hungary|Budapest|Szerverplex Kft|
|8|147.182.146.92|3128|Canada|Toronto|DigitalOcean, LLC|
|9|195.154.255.194|8000|France|Vitry-sur-Seine|Online S.A.S.|
|10|45.170.101.2|999|Chile|Buin|Fibernet SPA|
|11|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|12|59.98.4.70|8080|India|New Delhi|BSNL Internet|
|13|95.56.254.139|3128|Kazakhstan|Almaty|JSC Kazakhtelecom|
|14|89.132.144.41|9090|Hungary|Budapest|Vodafone Hungary Ltd.|
|15|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|16|124.156.122.42|8088|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|17|51.158.154.173|3128|France|Paris|SCALEWAY|
|18|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|19|168.138.211.5|8080|Japan|Tokyo|Oracle Corporation|
|20|1.179.148.9|55636|Thailand|Sam Phran|TOT Public Company Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6533** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|641|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|641|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|641|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1541|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|777|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2864|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|115.68.221.147|80|South Korea|Seoul|SMILESERV|
|2|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|3|112.217.162.5|3128|South Korea|Yangsan|LG DACOM Corporation|
|4|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|5|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|6|34.66.5.144|8888|United States|Council Bluffs|Google LLC|
|7|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|8|139.59.241.101|443|Singapore|Singapore|DigitalOcean, LLC|
|9|95.181.164.59|8080|Russia|Moscow|Yegor Andreevich trading as FLP Miglovets|
|10|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|11|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|12|95.154.104.147|44393|Russia|Vladivostok|Octopusnet Jurs|
|13|109.207.76.37|8080|Israel|Petah Tikva|O.M.C. COMPUTERS & COMMUNICATIONS LTD|
|14|178.33.198.181|3128|France|Strasbourg|OVH SAS|
|15|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|16|157.230.241.229|443|Singapore|Singapore|DigitalOcean, LLC|
|17|45.233.67.226|999|Guatemala|Jalapa|Conectividad Y Tecnologia S.A|
|18|45.32.69.105|3128|United States|Los Angeles|The Constant Company|
|19|213.145.150.77|8080|Kyrgyzstan|Bishkek|OJSC Kyrgyztelecom|
|20|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


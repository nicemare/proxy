
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5816** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|401|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|401|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|401|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1385|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|629|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2751|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|151.248.115.5|3128|Russia|Moscow|Reg.Ru|
|2|45.32.69.105|3128|United States|Los Angeles|The Constant Company|
|3|47.243.180.142|808|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|4|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|5|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|6|210.245.124.131|5239|Vietnam|Ho Chi Minh City|FPT Telecom Company|
|7|143.198.56.234|443|United States|Santa Clara|DigitalOcean, LLC|
|8|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|9|222.234.220.170|3128|South Korea|Seoul|SK Broadband Co Ltd|
|10|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|11|203.115.106.84|8080|India|Greater Noida|PRIMENET|
|12|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|13|112.87.140.164|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|14|186.96.167.253|999|Mexico|Texcoco|Total Play Telecomunicaciones SA De CV|
|15|191.102.64.146|999|Colombia|Manizales|TV AZTECA SUCURSAL COLOMBIA|
|16|41.242.116.150|50000|Mayotte|Mamoudzou|STOI-block1|
|17|109.110.35.210|9090|Russia|Vladivostok|Podryad Nets|
|18|8.242.176.196|999|Colombia|Santiago de Cali|CTL Colombia|
|19|176.214.97.55|1256|Russia|Moscow|Enforta-MSK|
|20|89.132.144.41|9090|Hungary|Budapest|Vodafone Hungary Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


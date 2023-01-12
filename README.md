
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6151** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|330|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|330|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|330|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1354|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|712|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2734|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|3|5.9.139.204|20000|Germany|Falkenstein|Hetzner Online GmbH|
|4|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|5|45.32.69.105|3128|United States|Los Angeles|The Constant Company|
|6|191.97.6.211|999|Colombia|Solano|TV AZTECA SUCURSAL COLOMBIA|
|7|195.201.147.185|8084|Germany|Gunzenhausen|Hetzner Online GmbH|
|8|23.229.80.47|3129|United States|Buffalo|B2 Net Solutions Inc.|
|9|23.229.80.219|3129|United States|Buffalo|B2 Net Solutions Inc.|
|10|23.229.80.149|3129|United States|Buffalo|B2 Net Solutions Inc.|
|11|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|12|62.171.189.81|80|Germany|Nuremberg|Contabo GmbH|
|13|61.178.141.146|80|China|Yuzhong Chengguanzhen|Chinanet|
|14|128.199.67.35|80|Singapore|Singapore|DigitalOcean, LLC|
|15|95.0.90.243|8080|Turkey|Istanbul|Turk Telekomunikasyon Anonim Sirketi|
|16|103.243.114.206|8080|India|Beed|Gazon Communications India Limited|
|17|23.229.80.7|3129|United States|Buffalo|B2 Net Solutions Inc.|
|18|188.133.152.125|8080|Russia|Moscow|Enforta-MSK|
|19|86.110.27.165|3128|Russia|Moscow|Digit One LLC|
|20|46.191.235.167|443|Russia|Ufa|JSC "Ufanet"|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


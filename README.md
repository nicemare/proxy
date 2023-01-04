
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6379** proxies at the latest update. Usable proxies are below.

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1641|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|682|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2705|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|151.248.115.5|3128|Russia|Moscow|Reg.Ru|
|3|66.42.53.233|8000|Singapore|Singapore|The Constant Company|
|4|51.159.115.233|3128|France|Paris|SCALEWAY|
|5|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|6|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|7|45.32.69.105|3128|United States|Los Angeles|The Constant Company|
|8|116.58.239.202|53281|Thailand|Ban Kao|CAT-BB|
|9|195.201.147.185|8084|Germany|Gunzenhausen|Hetzner Online GmbH|
|10|143.198.56.234|443|United States|Santa Clara|DigitalOcean, LLC|
|11|112.194.89.48|44406|China|Chengdu|China Unicom CHINA169 Sichuan Province Network|
|12|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|13|181.143.225.173|3129|Colombia|Santiago de Cali|EPM Telecomunicaciones S.A. E.S.P.|
|14|103.11.106.48|8080|Indonesia|Madiun|PT. Pascal Indonesia|
|15|103.145.128.180|8088|Indonesia|Jakarta|PT. Indonesia Comnets Plus|
|16|221.225.81.91|3128|China|Shanghai|CHINANET jiangsu province network|
|17|63.250.53.181|3128|United Kingdom|London|HIVELOCITY, Inc.|
|18|86.110.27.165|3128|Russia|Moscow|Digit One LLC|
|19|112.87.140.164|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|20|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


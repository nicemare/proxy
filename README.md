
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6530** proxies at the latest update. Usable proxies are below.

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
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|2240|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|822|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2417|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|135.12.198.20|3128|United States|Sterling|Carrytel|
|2|135.12.194.221|3128|United States|Sterling|Carrytel|
|3|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|4|125.26.224.189|8080|Thailand|Khwaeng Thung Song Hong|TOT Public Company Limited|
|5|136.243.146.112|8080|Germany|Falkenstein|Hetzner Online GmbH|
|6|135.12.200.1|3128|United States|Sterling|Carrytel|
|7|112.87.140.163|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|8|112.87.140.163|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|9|31.161.38.233|8090|Netherlands|Doetinchem|KPN B.V|
|10|186.148.181.54|999|Colombia|Bogotá|TV AZTECA SUCURSAL COLOMBIA|
|11|102.177.192.84|3128|Zimbabwe|Harare|Contitouch Zimbabwe|
|12|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|13|103.43.1.0|3129|Indonesia|Pondok Pinang|PT Daya Sinergi Telekomunikasi|
|14|190.128.129.10|8080|Paraguay|Asunción|Telecel S.A.|
|15|45.174.70.18|53281|Mexico|Huatabampo|Index Datacom S.a. De C.V.|
|16|24.172.82.94|53281|United States|Huntersville|Spectrum|
|17|80.194.38.106|3333|United Kingdom|London|Virgin Media Limited|
|18|43.243.172.2|83|India|Pune|Shah Solutions|
|19|51.158.154.173|3128|France|Paris|SCALEWAY|
|20|181.129.49.214|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


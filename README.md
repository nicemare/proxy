
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6198** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|223|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|223|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|223|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1607|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1123|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2417|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|2|200.119.89.19|80|Colombia|Bogotá|ETB - Colombia|
|3|18.219.23.232|3128|United States|Dublin|Amazon.com, Inc.|
|4|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|5|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|6|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|7|112.87.140.163|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|8|112.87.140.164|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|9|191.97.14.26|999|Colombia|Bogotá|TV AZTECA SUCURSAL COLOMBIA|
|10|93.91.112.247|41258|Russia|Tver|Fast Link Ltd.|
|11|185.212.193.162|8080|Iran|Kermanshah|Hesabgar Pardaz Gharb PJSC|
|12|181.129.49.214|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|13|190.61.84.166|9812|Costa Rica|San José|Ufinet Costa Rica|
|14|112.87.140.163|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|15|51.158.154.173|3128|France|Paris|SCALEWAY|
|16|91.82.247.150|9999|Hungary|Labatlan|INVITEL Zrt.|
|17|200.106.187.246|999|Argentina|Jose Maria Ezeiza|Fullnet Solutions S.A.S.|
|18|200.85.198.9|999|Chile|Puyehue|Telefonica del Sur S.A.|
|19|1.179.136.98|8080|Thailand|Ayutthaya|TOT Public Company Limited|
|20|104.192.202.11|8080|United States|St. George|InfoWest|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


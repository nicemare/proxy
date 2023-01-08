
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6070** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|512|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|512|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|512|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1527|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|579|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2613|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|206.127.254.245|3129|United States|Glendale|Spartan Host Ltd|
|3|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|4|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|5|141.147.158.11|8080|Japan|Osaka|Oracle Corporation|
|6|94.20.38.130|3128|Azerbaijan|Baku|Delta Telecom|
|7|107.172.73.179|7890|United States|Buffalo|ColoCrossing|
|8|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|9|107.172.73.179|7890|United States|Buffalo|ColoCrossing|
|10|206.127.254.245|3129|United States|Glendale|Spartan Host Ltd|
|11|212.80.213.94|8080|Thailand|Nonthaburi|Siamdata Communication Co.|
|12|152.70.252.224|8080|South Korea|Seoul|Oracle Corporation|
|13|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|14|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|15|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|16|134.238.252.143|8080|India|Mumbai|Google LLC|
|17|34.84.172.172|3128|Japan|Tokyo|Google LLC|
|18|177.82.85.209|3128|Brazil|Ribeirão Preto|Claro NXT Telecomunicacoes Ltda|
|19|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|20|45.130.141.59|8080|United Kingdom|London|Bangmod Enterprise Co., Ltd.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


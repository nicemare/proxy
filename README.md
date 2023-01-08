
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6170** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|303|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|303|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|303|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1322|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|720|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2777|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|34.146.19.255|3128|Japan|Tokyo|Google LLC|
|3|177.82.85.209|3128|Brazil|Ribeirão Preto|Claro NXT Telecomunicacoes Ltda|
|4|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|5|5.135.240.70|8080|France|Nozay|OVH SAS|
|6|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|7|112.87.140.164|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|8|181.198.40.18|999|Ecuador|Montalvo|Telconet S.A|
|9|89.107.197.164|3128|Russia|Tula|LLC TK Altair|
|10|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|11|41.59.97.53|9999|Tanzania|Arusha|TTCL|
|12|41.242.116.150|50000|Mayotte|Mamoudzou|STOI-block1|
|13|34.91.252.109|80|Netherlands|Groningen|Google LLC|
|14|115.182.62.247|7890|China|Beijing|Beijing Dian-Xin-Tong Network Technologies Co., Ltd.|
|15|20.121.184.238|9401|United States|Boydton|Microsoft Corporation|
|16|95.56.254.139|3128|Kazakhstan|Almaty|JSC Kazakhtelecom|
|17|110.171.84.180|8080|Thailand|Thon Buri|True Internet Corporation CO. Ltd.|
|18|167.172.148.49|3128|United States|North Bergen|DigitalOcean, LLC|
|19|111.225.152.202|8089|China|Gaocheng|Chinanet|
|20|205.185.113.252|3128|United States|Las Vegas|FranTech Solutions|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5483** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|211|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|211|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|211|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|767|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|853|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2812|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|2|200.187.169.78|3128|Brazil|Fortaleza|ALGAR TELECOM S/A|
|3|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|4|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|5|179.95.235.58|8080|Brazil|Campo Grande|Vivo|
|6|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|7|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|8|125.25.32.129|8080|Thailand|Chiang Mai|TOT Public Company Limited|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|45.91.133.137|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|96.36.109.242|8080|United States|Roanoke Rapids|Charter Communications|
|13|5.234.183.29|8080|Iran|Piranshahr|Iran Telecommunication Company PJS|
|14|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|15|106.227.51.67|9002|China|Dunhou|China Telecom|
|16|61.178.141.146|80|China|Yuzhong Chengguanzhen|Chinanet|
|17|203.153.105.239|3128|Indonesia|Tangerang|PT NettoCyber Indonesia|
|18|101.226.20.25|9002|China|Shanghai|China Telecom (Group)|
|19|213.87.106.117|3128|Russia|Tynda|Vladivostok division of Mobile Telesystems OJSC|
|20|38.54.50.232|8080|Japan|Tokyo|Kaopu Cloud HK Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


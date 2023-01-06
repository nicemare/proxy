
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5610** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|393|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|393|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|393|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1085|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|597|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2577|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|3|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|4|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|5|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|6|45.156.29.56|9090|Turkey|Istanbul|Atlantis Telekomunikasyon Bilisim Hizmetleri San. Tic. Ltd|
|7|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|8|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|45.91.133.137|8080|Thailand|Nonthaburi|Siamdata Communication Co., ltd.|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|13|47.252.4.64|8888|United States|Charlottesville|Alibaba.com LLC|
|14|103.9.156.113|3128|Vietnam|Ho Chi Minh City|Vnso Technology Company|
|15|149.57.11.17|8181|United States|Frankton|J2 Technology LLC|
|16|103.9.156.99|3128|Vietnam|Ho Chi Minh City|Vnso Technology Company|
|17|61.178.141.146|80|China|Yuzhong Chengguanzhen|Chinanet|
|18|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|19|103.189.116.21|8080|Indonesia|Tipar|PT Callysta Total Solusindo|
|20|213.171.63.210|41890|Russia|Moscow|OJSC Comcor|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


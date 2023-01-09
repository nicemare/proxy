
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6420** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|635|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|635|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|635|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1632|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|994|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2711|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|161.35.48.185|443|United States|North Bergen|DigitalOcean, LLC|
|2|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|3|143.198.166.215|3128|United States|North Bergen|DigitalOcean, LLC|
|4|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|5|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|6|23.115.254.221|8080|United States|Miami|AT&T Services, Inc.|
|7|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|8|107.172.73.179|7890|United States|Buffalo|ColoCrossing|
|9|200.229.147.2|999|Honduras|Comayagua|Ufinet Panama S.A.|
|10|200.7.10.158|8080|Brazil|Itumbiara|Conexao Telematica LTDA|
|11|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|12|206.127.254.245|3129|United States|Glendale|Spartan Host Ltd|
|13|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|14|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|15|116.202.165.119|3121|Germany|Falkenstein|Hetzner Online GmbH|
|16|171.103.58.122|8080|Thailand|Bangkok|True Internet Co., Ltd.|
|17|144.24.207.98|8080|France|Marseille|Oracle Corporation|
|18|200.13.22.210|80|Mexico|Silao|Marcatel Com, S.A. de C.V.|
|19|89.132.144.41|9090|Hungary|Budapest|Vodafone Hungary Ltd.|
|20|104.223.135.178|10000|United States|Los Angeles|LayerHost|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


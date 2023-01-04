
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6060** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|344|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|344|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|344|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1328|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|612|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2769|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|168.235.85.81|18888|United States|Los Angeles|InMotion Hosting, Inc.|
|2|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|5|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|6|168.235.85.81|18888|United States|Los Angeles|InMotion Hosting, Inc.|
|7|44.230.152.143|80|United States|Portland|Amazon.com, Inc.|
|8|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|9|202.40.177.69|80|Bangladesh|Dhaka|Ranks ITT|
|10|111.225.153.14|8089|China|Gaocheng|Chinanet|
|11|47.252.4.64|8888|United States|Charlottesville|Alibaba.com LLC|
|12|181.129.49.214|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|13|103.189.116.21|8080|Indonesia|Tipar|PT Callysta Total Solusindo|
|14|49.212.143.246|6666|Japan|Yokohama|SAKURA Internet Inc.|
|15|36.89.156.146|8080|Indonesia|Jakarta|PT. Telekomunikasi Indonesia|
|16|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|17|111.225.153.229|8089|China|Gaocheng|Chinanet|
|18|200.13.22.210|80|Mexico|Silao|Marcatel Com, S.A. de C.V.|
|19|154.13.4.80|59394|Canada|Montreal|Zhihua Lu|
|20|106.227.48.205|9002|China|Dunhou|China Telecom|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


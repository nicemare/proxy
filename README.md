
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5812** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|297|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|297|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|297|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1280|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|778|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2403|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|205.209.99.153|80|United States|Englewood Cliffs|Interserver, Inc|
|2|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|3|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|4|151.248.115.5|3128|Russia|Moscow|Reg.Ru|
|5|94.237.3.45|8086|Singapore|Singapore|UpCloud Ltd|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|35.221.104.58|3128|Japan|Tokyo|Google LLC|
|8|129.205.182.213|8081|South Africa|Cape Town|Seacom Western Cape (Pty) Ltd|
|9|47.252.4.64|8888|United States|Charlottesville|Alibaba.com LLC|
|10|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|11|112.87.140.163|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|12|112.87.140.163|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|13|112.87.140.164|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|14|187.190.252.248|999|Mexico|Mexico City|Total Play Telecomunicaciones SA De CV|
|15|112.87.140.164|9443|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|16|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|17|61.216.156.222|60808|Taiwan|New Taipei|Chunghwa Telecom Co., Ltd.|
|18|181.129.49.214|999|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|19|38.49.128.114|999|Mexico|Apaseo el Alto|Ientc S De RL De CV|
|20|51.158.154.173|3128|France|Paris|SCALEWAY|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


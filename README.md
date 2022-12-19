
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5820** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|503|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|503|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|503|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1225|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|704|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2640|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|2|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|3|157.245.27.9|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|
|4|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|5|167.71.72.97|3128|Netherlands|Amsterdam|DigitalOcean, LLC|
|6|75.126.253.8|8080|United States|Dallas|SoftLayer|
|7|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|8|130.255.138.245|8080|Ukraine|Sevastopol|Lancom Ltd.|
|9|85.195.104.71|80|Germany|Frankfurt am Main|Host Europe GmbH|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|145.40.121.73|3128|Brazil|São Paulo|Packet Host, Inc.|
|12|185.81.98.16|3131|Netherlands|Naaldwijk|WorldStream B.V.|
|13|158.69.27.94|9300|Canada|Montreal|OVH SAS|
|14|92.241.102.47|3128|Russia|Khislavichi|SMOLTELECOM|
|15|5.39.105.211|3128|France|Lyon|OVH SAS|
|16|171.6.144.138|8080|Thailand|Bang Bua Thong|Triple T Broadband Public Company Limited|
|17|5.160.179.8|8080|Iran|Tehran|Respina Networks & Beyond PJSC|
|18|45.229.34.174|999|Dominican Republic|Santo Domingo Este|Gold Data C.A.|
|19|103.16.160.70|10000|Vietnam|Chúc Sơn|ANH|
|20|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


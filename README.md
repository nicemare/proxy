
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5095** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|377|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|377|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|377|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|802|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|480|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2462|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|4|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|5|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|157.100.12.138|999|Ecuador|Loja|Telconet S.A|
|8|35.193.113.186|80|United States|Council Bluffs|Google LLC|
|9|45.76.8.6|8080|United States|Piscataway|The Constant Company|
|10|75.126.253.8|8080|United States|Dallas|SoftLayer|
|11|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|12|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|13|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|14|119.8.236.97|3128|Hong Kong|Hong Kong|Huawei International Pte. Ltd.|
|15|154.16.180.182|3128|United States|Dulles|LYIT Internet Services|
|16|155.4.244.218|80|Sweden|Stockholm|Bahnhof AB|
|17|134.73.3.33|3129|United States|Los Angeles|LayerHost|
|18|107.172.73.179|7890|Canada|Hamilton|ColoCrossing|
|19|51.159.115.233|3128|France|Paris|SCALEWAY|
|20|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


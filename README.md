
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5129** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|406|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|406|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|406|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|787|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|411|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2580|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|170.178.220.210|3128|United States|Santa Clarita|Multacom Corporation|
|5|185.156.98.70|30001|Denmark|Tønder|WNB A/S|
|6|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|7|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|8|75.126.253.8|8080|United States|Dallas|SoftLayer|
|9|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|10|52.87.136.220|80|United States|Ashburn|Amazon.com, Inc.|
|11|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|12|119.8.236.97|3128|Hong Kong|Hong Kong|Huawei International Pte. Ltd.|
|13|134.238.252.143|8080|India|Mumbai|Google LLC|
|14|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|15|176.196.250.86|3128|Russia|Kemerovo|Goodline.info|
|16|107.172.73.179|7890|Canada|Hamilton|ColoCrossing|
|17|195.3.245.193|3128|Russia|Simferopol|CrimeaCom South LLC|
|18|172.94.125.104|3128|Germany|Frankfurt am Main|Secure Internet LLC|
|19|172.105.216.60|443|Japan|Tokyo|Linode, LLC|
|20|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


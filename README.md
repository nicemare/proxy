
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5146** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|421|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|421|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|421|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1112|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|522|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2561|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|2|193.122.134.214|80|United States|Ashburn|Oracle Corporation|
|3|51.159.115.233|3128|France|Paris|SCALEWAY|
|4|59.21.53.212|4001|South Korea|Buk-gu|Korea Telecom|
|5|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|6|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|7|171.224.76.124|4003|Vietnam|Thai Binh|Viettel Corporation|
|8|145.40.121.89|3128|Brazil|São Paulo|Packet Host, Inc.|
|9|31.6.69.119|39811|Poland|Tarnowskie Gory|Livenet sp. z o.o.|
|10|64.227.7.192|3128|United States|North Bergen|DigitalOcean, LLC|
|11|183.80.180.218|4001|Vietnam|Hanoi|FPT Telecom Company|
|12|103.4.164.204|8080|Indonesia|Jakarta|FIBERNET|
|13|193.122.134.214|80|United States|Ashburn|Oracle Corporation|
|14|145.40.121.167|3128|Brazil|São Paulo|Packet Host, Inc.|
|15|145.40.121.157|3128|Brazil|São Paulo|Packet Host, Inc.|
|16|154.85.55.174|3128|United States|Los Angeles|Beijing Baidu Netcom Science and Technology Co., Ltd.|
|17|46.246.84.6|8118|Sweden|Stockholm|Portlane Network|
|18|212.46.230.102|6969|Russia|Moscow|PJSC "Vimpelcom"|
|19|134.238.252.143|8080|India|Mumbai|Google LLC|
|20|103.231.241.102|3128|Philippines|Quezon City|De La Salle University|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


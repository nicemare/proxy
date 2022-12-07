
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4567** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|256|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|256|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|256|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|695|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|287|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2234|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|45.152.188.16|3128|United States|Ashburn|Sprint|
|3|116.203.202.160|8443|Germany|Nuremberg|Hetzner Online GmbH|
|4|188.34.181.148|3897|Germany|Nuremberg|Hetzner Online GmbH|
|5|23.88.34.57|3897|Germany|Gunzenhausen|Hetzner Online GmbH|
|6|178.170.47.86|3128|France|Boulogne-Billancourt|Ikoula Net SAS|
|7|194.94.196.138|80|Germany|Bonn|Verein zur Foerderung eines Deutschen Forschungsnetzes e.V.|
|8|194.163.45.239|3128|United States|Phoenix|Hostinger International Limited|
|9|194.94.196.139|80|Germany|Bonn|Verein zur Foerderung eines Deutschen Forschungsnetzes e.V.|
|10|80.252.5.34|7001|Poland|Warsaw|GWNET Autonomus System|
|11|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|12|45.152.188.16|3128|United States|Ashburn|Sprint|
|13|147.135.134.57|9300|France|Gravelines|OVH SAS|
|14|181.215.178.58|1337|Netherlands|Amsterdam|NovoServe B.V.|
|15|134.238.252.143|8080|India|Mumbai|Google LLC|
|16|49.48.125.151|8080|Thailand|Ban Kho|Triple T Broadband Public Company Limited|
|17|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|18|160.16.130.191|3128|Japan|Tokyo|SAKURA Internet Inc.|
|19|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|20|103.160.232.122|8080|India|Thrissur|Highrange Digital Communicators Llp|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


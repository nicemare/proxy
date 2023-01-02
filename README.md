
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5672** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|300|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|300|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|300|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1153|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|552|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2616|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.63.254|3128|United States|Ashburn|Bernardi Sounds|
|2|136.243.138.231|3128|Germany|Falkenstein|Hetzner Online GmbH|
|3|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|4|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|5|134.238.252.143|8080|India|Mumbai|Google LLC|
|6|208.82.62.32|3128|United States|Ashburn|Bernardi Sounds|
|7|110.78.112.198|8080|Thailand|Ratchathewi|CAT Telecom Public Company Limited|
|8|80.244.226.92|8080|Russia|Moscow|Enforta-MSK|
|9|177.52.221.125|3128|Dominican Republic|Santiago de los Caballeros|TELERY NETWORKS, S.R.L|
|10|44.204.136.204|3128|United States|Ashburn|Amazon.com|
|11|107.173.156.182|3000|United States|San Jose|ColoCrossing|
|12|116.104.210.171|4015|Vietnam|Hanoi|Viettel Corporation|
|13|77.236.237.177|8080|Russia|Moscow|Enforta-MSK|
|14|5.9.94.91|3128|Germany|Falkenstein|Hetzner Online GmbH|
|15|198.144.149.82|3128|Canada|Toronto|Netminders Server Hosting|
|16|50.201.51.216|8080|United States|Pittsburgh|Comcast Cable Communications, LLC|
|17|195.154.255.194|8000|France|Vitry-sur-Seine|Online S.A.S.|
|18|117.4.115.169|8080|Vietnam|Phu Tu Son|Viettel Corporation|
|19|195.178.197.20|8080|Russia|Podolsk|IIP|
|20|185.20.198.250|8080|Iraq|Basrah|Horizon Scope Mobile Telecom WLL|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


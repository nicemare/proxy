
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5359** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|422|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|422|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|422|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|899|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|493|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2616|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.62.32|3128|United States|Ashburn|Bernardi Sounds|
|2|142.4.215.171|3128|Canada|Beauharnois|OVH SAS|
|3|178.33.198.181|3128|France|Strasbourg|OVH SAS|
|4|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|5|151.248.115.5|3128|Russia|Moscow|Reg.Ru|
|6|34.146.19.255|3128|Japan|Tokyo|Google LLC|
|7|208.82.63.254|3128|United States|Ashburn|Bernardi Sounds|
|8|103.144.161.100|8088|Bangladesh|Dhaka|Bismillah Telecom|
|9|5.78.43.246|80|United States|Portland|Hetzner Online GmbH|
|10|64.56.216.81|8080|United States|Winona|Upchurch Telecom & Data, Inc.|
|11|50.236.203.15|8080|United States|Peru|Comcast Cable Communications, LLC|
|12|103.210.161.198|8998|Hong Kong|Central|China Unicom Guangdong IP network|
|13|105.112.135.166|8080|Nigeria|Lagos|Airtel Networks Limited|
|14|103.189.116.21|8080|Indonesia|Tipar|PT Callysta Total Solusindo|
|15|51.79.50.22|9300|Canada|Beauharnois|OVH SAS|
|16|107.173.156.182|3000|United States|San Jose|ColoCrossing|
|17|44.204.136.204|3128|United States|Ashburn|Amazon.com|
|18|105.112.191.250|3128|Nigeria|Lagos|Airtel Networks Limited|
|19|49.212.143.246|6666|Japan|Yokohama|SAKURA Internet Inc.|
|20|149.28.132.9|10000|Singapore|Singapore|The Constant Company|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


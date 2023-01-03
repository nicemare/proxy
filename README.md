
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5536** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|442|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|442|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|442|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1130|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|584|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2771|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|3|35.200.4.163|3128|Japan|Tokyo|Google LLC|
|4|138.2.8.164|8000|Japan|Tokyo|Oracle Corporation|
|5|34.146.180.162|3128|Japan|Tokyo|Google LLC|
|6|109.194.101.128|3128|Russia|Yoshkar-Ola|CJSC "ER-Telecom Holding" Yoshkar-Ola branch|
|7|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|8|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|9|195.225.232.8|6053|Iran|Tehran|TS Information Technology Limited|
|10|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|11|96.68.234.217|8080|United States|Springfield|Comcast Cable Communications, LLC|
|12|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|13|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|14|46.31.77.223|3128|Turkey|Gaziosmanpasa|Talha Bogaz|
|15|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|16|194.145.138.18|9090|Turkey|Istanbul|Atlantis Telekomunikasyon Bilisim Hizmetleri San. Tic. Ltd|
|17|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|18|134.238.252.143|8080|India|Mumbai|Google LLC|
|19|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|20|149.28.132.9|10000|Singapore|Singapore|The Constant Company|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


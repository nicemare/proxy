
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4600** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|288|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|288|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|288|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|824|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|368|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2457|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|2|37.120.192.154|8080|Netherlands|Amsterdam|M247 Europe SRL|
|3|194.233.84.239|80|Singapore|Singapore|Contabo Asia Private Limited|
|4|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|5|134.238.252.143|8080|India|Mumbai|Google LLC|
|6|181.78.65.238|999|Colombia|Bogotá|IFX Networks Argentina S.R.L|
|7|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|8|210.179.58.236|80|South Korea|Naju-si|Korea Telecom|
|9|185.81.98.17|3131|Netherlands|Naaldwijk|WorldStream B.V.|
|10|1.53.252.228|2022|Vietnam|Ho Chi Minh City|FPT Telecom Company|
|11|181.78.65.250|999|Colombia|Bogotá|IFX Networks Argentina S.R.L|
|12|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|13|145.40.121.157|3128|Brazil|São Paulo|Packet Host, Inc.|
|14|145.40.121.91|3128|Brazil|São Paulo|Packet Host, Inc.|
|15|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|16|51.79.50.22|9300|Canada|Beauharnois|OVH SAS|
|17|110.34.3.229|3128|Nepal|Kathmandu|SUBISU C7|
|18|103.151.177.106|80|Indonesia|Jakarta|PT JASAMARGA TOLLROAD OPERATOR|
|19|193.122.134.214|80|United States|Ashburn|Oracle Corporation|
|20|181.143.106.162|52151|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


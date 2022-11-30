
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5010** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|301|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|301|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|301|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|731|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|401|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2527|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|51.222.75.219|8080|Canada|Beauharnois|OVH Hosting|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|119.8.236.97|3128|Hong Kong|Hong Kong|Huawei International Pte. Ltd.|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|7|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|8|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|155.4.244.218|80|Sweden|Stockholm|Bahnhof AB|
|11|43.135.156.130|59394|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|12|90.166.42.65|1234|Spain|Torre Pacheco|Uni2|
|13|51.159.115.233|3128|France|Paris|SCALEWAY|
|14|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|15|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|16|195.154.255.194|8000|France|Vitry-sur-Seine|Online S.A.S.|
|17|74.82.50.155|3128|Japan|Shinagawa|Hurricane Electric|
|18|103.231.241.102|80|Philippines|Quezon City|De La Salle University|
|19|201.220.102.146|8080|Chile|Talca|Telefonica del Sur S.A.|
|20|161.53.129.23|3128|Croatia|Krapinske Toplice|Croatian Academic and Research Network|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


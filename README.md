
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4432** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|261|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|261|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|261|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|511|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|282|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2388|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|185.81.98.17|3131|Netherlands|Naaldwijk|WorldStream B.V.|
|2|54.202.43.221|3128|United States|Portland|Amazon.com, Inc.|
|3|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|4|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|194.195.90.215|8118|Singapore|Singapore|Contabo Asia Private Limited|
|7|54.202.43.221|3128|United States|Portland|Amazon.com, Inc.|
|8|172.104.128.235|8888|Germany|Frankfurt am Main|Linode, LLC|
|9|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|10|82.99.194.30|3128|Iran|Khorramshahr|ParsOnline Co.|
|11|196.15.213.235|3128|South Africa|Christiana|Telkom SA Ltd.|
|12|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|13|160.16.130.191|3128|Japan|Tokyo|SAKURA Internet Inc.|
|14|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|15|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|16|201.229.250.19|8080|Dominican Republic|Santiago de los Caballeros|Compañía Dominicana de Teléfonos S. A.|
|17|46.246.84.3|8118|Sweden|Stockholm|Portlane Network|
|18|212.174.242.114|8080|Turkey|Adana|TurkTelecom|
|19|31.186.48.232|3128|Kyrgyzstan|Bishkek|AKNET Ltd.|
|20|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


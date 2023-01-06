
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6228** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|601|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|601|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|601|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1128|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1085|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2664|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.237.154.46|80|United States|Fremont|Linode, LLC|
|2|102.177.192.84|3128|Zimbabwe|Harare|Contitouch Zimbabwe|
|3|200.170.138.194|3128|Brazil|Patos de Minas|ALGAR TELECOM S/A|
|4|34.245.27.31|3128|Ireland|Dublin|Amazon Technologies Inc.|
|5|43.132.202.254|8080|Hong Kong|Hong Kong|Shenzhen Tencent Computer Systems Company Limited|
|6|104.237.154.46|80|United States|Fremont|Linode, LLC|
|7|190.119.203.220|8080|Peru|La Victoria|America Movil Peru S.A.C.|
|8|93.157.51.19|8080|Germany|Frankfurt am Main|GHOSTnet Ackermann-EDV|
|9|145.40.121.153|3128|Brazil|São Paulo|Packet Host, Inc.|
|10|185.198.61.146|3128|Italy|Milan|Global Router LLC|
|11|93.84.68.62|3128|Belarus|Gomel|Republican Unitary Telecommunication Enterprise Beltelecom|
|12|170.0.54.249|8080|Brazil|Olho d'Agua das Cunhas|Telecom Scae Ltda|
|13|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|14|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|15|61.198.92.244|8080|Japan|Kanazawa|NSK Co., Ltd.|
|16|49.0.2.242|8090|Indonesia|Bogor|PT Usaha Adi Sanggoro|
|17|20.210.26.214|3128|Japan|Tokyo|Microsoft Corporation|
|18|83.171.236.79|8080|Germany|Schwielowsee|Droptop GmbH|
|19|141.147.158.11|8080|Japan|Osaka|Oracle Corporation|
|20|93.170.0.71|8080|Ukraine|Lviv|PE Galician Information Networks|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


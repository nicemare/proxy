
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5036** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|135|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|135|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|135|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|929|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|191|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2665|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|49.0.2.242|8090|Indonesia|Cikarawang|PT Usaha Adi Sanggoro|
|4|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|5|157.100.12.138|999|Ecuador|Celica|Telconet S.A|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|200.69.83.23|8080|Colombia|Bogotá|TV AZTECA SUCURSAL COLOMBIA|
|8|190.54.100.74|8080|Chile|Santiago|Telmex Chile Internet S.A.|
|9|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|10|154.19.187.251|3128|Japan|Tokyo|SICLOUD INFORMATION TECHNOLOGY (HONGKONG) CO., LIMITED|
|11|118.27.113.167|8080|Japan|Chiyoda|GMO Internet, Inc.|
|12|47.241.165.133|443|Singapore|Singapore|Alibaba.com LLC|
|13|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|14|167.71.190.253|80|United States|Clifton|DigitalOcean, LLC|
|15|103.220.206.110|59570|Bangladesh|Dhaka|KS Network|
|16|200.24.157.116|999|Ecuador|Azogues|Nedetel S.A.|
|17|178.151.205.154|45099|Ukraine|Zaporizhzhya|Triolan|
|18|172.105.226.115|443|Japan|Tokyo|Linode, LLC|
|19|115.147.17.246|8080|Philippines|Mandaluyong City|Philippine Long Distance Telephone Co.|
|20|187.44.167.78|60786|Brazil|Salvador|ITS TELECOMUNICACOES LTDA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


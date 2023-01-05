
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6789** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|212|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|212|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|212|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1648|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|833|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2957|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|129.213.95.20|80|United States|Ashburn|Oracle Corporation|
|2|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|3|51.159.115.233|3128|France|Paris|SCALEWAY|
|4|93.91.112.247|41258|Russia|Tver|Fast Link Ltd.|
|5|52.53.251.113|3128|United States|San Jose|Amazon.com, Inc.|
|6|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|7|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|8|103.178.43.102|8181|Indonesia|Jakarta Pusat|PT Jaring Solusi Persada|
|9|103.151.236.178|8080|Pakistan|Lahore|Fiberlink Pvt.Ltd|
|10|45.181.122.74|999|Chile|Santiago|Interpit Telecomunicaciones Ltda|
|11|51.195.81.233|8080|Germany|Limburg an der Lahn|OVH SAS|
|12|149.34.3.152|8080|Spain|Cunit|Adamo Telecom Iberia S.A.|
|13|109.207.76.37|8080|Israel|Petah Tikva|O.M.C. COMPUTERS & COMMUNICATIONS LTD|
|14|188.40.20.151|3128|Germany|Falkenstein|Hetzner Online GmbH|
|15|145.40.121.103|3128|Brazil|São Paulo|Packet Host, Inc.|
|16|194.87.188.114|8000|Turkey|Istanbul|Kadir Huseyin Tezcan Nosspeed Internet Teknolojileri|
|17|77.236.238.33|1256|Russia|Moscow|ArtCommunications Ltd.|
|18|82.66.75.98|49400|France|Paris|Proxad / Free SAS|
|19|79.111.13.155|50625|Russia|Moscow|Net By Net Holding LLC|
|20|20.121.184.238|9401|United States|Boydton|Microsoft Corporation|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


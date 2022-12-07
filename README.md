
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5358** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|306|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|306|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|306|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|943|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|429|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2735|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|45.152.188.16|3128|United States|Ashburn|Sprint|
|3|51.79.50.31|9300|Canada|Victoria|OVH SAS|
|4|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|5|191.102.117.202|999|Colombia|Bogotá|TV AZTECA SUCURSAL COLOMBIA|
|6|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|7|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|8|45.152.188.248|3128|United States|Ashburn|Sprint|
|9|45.152.188.16|3128|United States|Ashburn|Sprint|
|10|157.245.222.183|80|United States|Clifton|DigitalOcean, LLC|
|11|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|12|18.235.55.193|8080|United States|Ashburn|Amazon.com, Inc.|
|13|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|14|45.152.188.248|3128|United States|Ashburn|Sprint|
|15|185.217.137.241|1337|Seychelles|Cascade|Stallion Network Services Limited|
|16|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|17|14.207.122.96|8080|Thailand|Ban Sop Bua|Triple T Broadband Public Company Limited|
|18|139.28.37.94|8080|Ukraine|Kyiv|Zemlyaniy Dmitro Leonidovich|
|19|140.227.25.191|23456|Japan|Yonabaru|InfoSphere|
|20|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


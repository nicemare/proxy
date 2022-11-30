
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5512** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|416|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|416|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|416|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1138|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|472|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2551|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|2|49.51.90.57|3128|Canada|Barrie|OPHL|
|3|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|4|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|5|45.233.67.223|999|Guatemala|Jalapa|Conectividad Y Tecnologia S.A|
|6|68.183.131.244|8081|United States|North Bergen|DigitalOcean, LLC|
|7|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|8|164.92.160.38|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|9|75.126.253.8|8080|United States|Dallas|SoftLayer|
|10|52.87.136.220|80|United States|Ashburn|Amazon.com, Inc.|
|11|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|12|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|13|68.183.131.244|8081|United States|North Bergen|DigitalOcean, LLC|
|14|134.238.252.143|8080|India|Mumbai|Google LLC|
|15|176.192.70.58|8005|Russia|Moscow|Net By Net Holding LLC|
|16|157.245.205.156|443|Singapore|Singapore|DigitalOcean, LLC|
|17|62.76.26.232|3128|Russia|Moscow|Start LLC|
|18|154.16.180.182|3128|United States|Dulles|LYIT Internet Services|
|19|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|20|43.154.69.42|3128|Hong Kong|Hong Kong|Shenzhen Tencent Computer Systems Company Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


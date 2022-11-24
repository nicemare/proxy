
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **5450** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|427|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|427|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|427|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1151|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|429|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2519|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|208.82.61.13|3128|United States|Ashburn|Bernardi Sounds|
|2|170.39.118.22|3128|United States|Ashburn|Rackdog, LLC|
|3|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|4|208.82.61.38|3128|United States|Ashburn|Bernardi Sounds|
|5|208.82.61.31|3128|United States|Ashburn|Bernardi Sounds|
|6|75.126.253.8|8080|United States|Dallas|SoftLayer|
|7|208.82.61.12|3128|United States|Ashburn|Bernardi Sounds|
|8|130.83.47.201|3128|Germany|Alsbach-Hahnlein|TU-DARMSTADT via MANDA|
|9|5.189.184.6|80|Germany|Nuremberg|Contabo GmbH|
|10|54.249.186.103|80|Japan|Tokyo|Amazon.com, Inc.|
|11|204.185.204.64|8080|United States|Kansas City|org-morenet.more.net|
|12|208.82.61.12|3128|United States|Ashburn|Bernardi Sounds|
|13|158.69.53.98|9300|Canada|Montreal|OVH SAS|
|14|43.206.81.172|80|Japan|Tokyo|Amazon.com, Inc.|
|15|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|16|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|17|170.39.116.114|3128|United States|Ashburn|Rackdog, LLC|
|18|208.82.61.31|3128|United States|Ashburn|Bernardi Sounds|
|19|208.82.61.13|3128|United States|Ashburn|Bernardi Sounds|
|20|158.69.71.245|9300|Canada|Montreal|OVH SAS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


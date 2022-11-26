
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4275** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|146|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|146|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|146|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|364|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|114|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2446|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|170.39.116.114|3128|United States|Ashburn|Rackdog, LLC|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|138.201.35.213|1337|Germany|Falkenstein|Hetzner Online GmbH|
|4|141.94.137.176|1337|France|Gravelines|OVH SAS|
|5|192.99.34.64|1337|Canada|Beauharnois|OVH SAS|
|6|134.238.252.143|8080|India|Mumbai|Google LLC|
|7|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|8|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|9|170.39.116.114|3128|United States|Ashburn|Rackdog, LLC|
|10|148.251.184.47|1988|Germany|Falkenstein|Hetzner Online GmbH|
|11|148.251.236.80|1988|Germany|Falkenstein|Hetzner Online GmbH|
|12|144.76.119.59|1988|Germany|Falkenstein|Hetzner Online GmbH|
|13|136.243.3.245|1988|Germany|Falkenstein|Hetzner Online GmbH|
|14|46.4.24.111|1988|Germany|Falkenstein|Hetzner Online GmbH|
|15|148.251.66.8|1988|Germany|Falkenstein|Hetzner Online GmbH|
|16|51.159.28.133|8000|France|Paris|SCALEWAY|
|17|51.159.28.20|8000|France|Paris|SCALEWAY|
|18|161.97.97.155|3128|Germany|Nuremberg|Contabo GmbH|
|19|195.161.41.251|3128|Russia|Moscow|JSC RTComm.RU|
|20|82.194.3.83|3128|Azerbaijan|Baku|AzEduNet|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


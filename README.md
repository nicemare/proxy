
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **6900** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|911|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|911|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|911|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1196|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1372|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|3081|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|116.202.22.13|3128|Germany|Falkenstein|Hetzner Online GmbH|
|3|75.126.253.8|8080|United States|Dallas|SoftLayer|
|4|139.59.59.122|8118|India|Bengaluru|DIGITALOCEAN|
|5|152.231.20.49|999|Argentina|Villa Madero|CBRNET|
|6|51.159.115.233|3128|France|Paris|SCALEWAY|
|7|104.131.19.48|3128|United States|Clifton|DigitalOcean, LLC|
|8|159.89.196.22|443|Singapore|Singapore|DigitalOcean, LLC|
|9|172.105.216.60|443|Japan|Tokyo|Linode, LLC|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|112.140.186.124|808|Singapore|Singapore|Sparkstation Pte Ltd|
|12|187.130.139.197|8080|Mexico|Mazatlán|Uninet S.A. de C.V.|
|13|94.103.85.88|9300|Russia|Moscow|VDSINA|
|14|158.69.52.218|9300|Canada|Montreal|OVH SAS|
|15|91.108.137.237|8080|Iran|Behbahan|Rayaneh Gostar Farzanegan Ahvaz LTD|
|16|83.220.47.146|8080|Russia|Moscow|GARS|
|17|5.160.179.8|8080|Iran|Tehran|Respina Networks & Beyond PJSC|
|18|89.107.197.165|3128|Russia|Tula|LLC TK Altair|
|19|95.57.216.118|8080|Kazakhstan|Aktobe|JSC Kazakhtelecom|
|20|103.133.26.107|8181|Indonesia|Pajajaran|PT PHATRIA INTI PERSADA|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.



# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4402** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|223|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|223|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|223|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|573|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|294|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2184|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|75.126.253.8|8080|United States|Dallas|SoftLayer|
|2|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|3|209.97.158.134|8080|United States|Clifton|DigitalOcean, LLC|
|4|121.165.3.66|8080|South Korea|Suwon|Korea Telecom|
|5|75.126.253.8|8080|United States|Dallas|SoftLayer|
|6|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|7|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|8|140.82.5.38|1080|United States|Piscataway|The Constant Company|
|9|159.65.187.194|8080|United States|Clifton|DigitalOcean, LLC|
|10|134.238.252.143|8080|India|Mumbai|Google LLC|
|11|209.97.158.134|8080|United States|Clifton|DigitalOcean, LLC|
|12|43.135.156.130|59394|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|13|161.97.126.37|8118|Germany|Nuremberg|Contabo GmbH|
|14|87.247.186.105|80|Iran|Tehran|Insightometrics B.V.|
|15|51.159.115.233|3128|France|Paris|SCALEWAY|
|16|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|17|178.206.193.220|8080|Russia|Leninogorsk|PJSC "TATTELECOM"|
|18|75.126.253.8|8080|United States|Dallas|SoftLayer|
|19|148.251.184.47|1988|Germany|Falkenstein|Hetzner Online GmbH|
|20|47.242.43.30|1080|Hong Kong|Hong Kong|Alibaba.com LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


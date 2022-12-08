
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4304** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|191|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|191|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|191|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|405|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|285|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2363|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|116.203.202.160|8443|Germany|Nuremberg|Hetzner Online GmbH|
|2|75.126.253.8|8080|United States|Dallas|SoftLayer|
|3|129.226.15.129|80|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|4|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|5|115.96.208.124|8080|India|Mumbai|Hathway IP over Cable Internet Access|
|6|103.53.76.66|8080|Indonesia|Surabaya|INTI|
|7|134.238.252.143|8080|India|Mumbai|Google LLC|
|8|45.152.188.16|3128|United States|Ashburn|Sprint|
|9|45.152.188.16|3128|United States|Ashburn|Sprint|
|10|208.82.61.66|3128|United States|Ashburn|Bernardi Sounds|
|11|64.225.97.57|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|12|34.140.197.165|8080|Belgium|Brussels|Google LLC|
|13|45.167.125.61|9992|Colombia|Popayán|Sepcom Comunicaciones SAS|
|14|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|15|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|
|16|5.160.179.8|8080|Iran|Tehran|Respina Networks & Beyond PJSC|
|17|5.16.1.7|1256|Russia|Moscow|Enforta-MSK|
|18|45.152.188.16|3128|United States|Ashburn|Sprint|
|19|157.100.12.138|999|Ecuador|Loja|Telconet S.A|
|20|116.203.202.160|8443|Germany|Nuremberg|Hetzner Online GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


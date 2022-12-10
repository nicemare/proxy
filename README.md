
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.


> Scraper found **4664** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.


|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|302|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|302|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|302|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|697|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|332|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2384|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|31.186.239.245|8080|Netherlands|Amsterdam|NetSkope Inc|
|2|89.36.94.242|1337|Romania|Lipova|Interkvm Host SRL|
|3|185.143.146.171|8080|Ukraine|Kyiv|ISP UTELS|
|4|75.126.253.8|8080|United States|Dallas|SoftLayer|
|5|93.114.194.26|1337|Romania|Lipova|Interkvm Host SRL|
|6|185.8.165.134|8800|Czechia|Prague|Master Internet s.r.o.|
|7|181.215.178.58|1337|Netherlands|Amsterdam|NovoServe B.V.|
|8|47.241.66.249|1081|Singapore|Singapore|Alibaba.com LLC|
|9|134.238.252.143|8080|India|Mumbai|Google LLC|
|10|45.147.77.77|8118|Iran|Tehran|Pars Parva System LLC|
|11|165.255.89.66|8888|South Africa|Pretoria|Afrihost (Pty) Ltd|
|12|177.87.144.122|9898|Brazil|Sao Jose do Rio Pardo|Conexao Servicos De Comunicacao Multimidia Ltda-me|
|13|112.78.164.218|8080|Indonesia|Jakarta|Biznet Networks|
|14|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|15|171.6.76.241|8080|Thailand|Si Racha|Triple T Broadband Public Company Limited|
|16|31.186.48.232|3128|Kyrgyzstan|Bishkek|AKNET Ltd.|
|17|158.69.71.245|9300|Canada|Montreal|OVH SAS|
|18|31.186.239.246|8080|Netherlands|Amsterdam|NetSkope Inc|
|19|31.186.239.244|8080|Netherlands|Amsterdam|NetSkope Inc|
|20|178.209.51.218|7829|Switzerland|Zurich|Nine Internet Solutions AG|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.


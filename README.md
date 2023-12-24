# HTTPS-Deployment
This focuses on the various way of securing your websites with HTTPS
<br/>

Setting up HTTPS on your website can be done either with or without purchasing a custom domain name

<br/>

## HTTPS without purchasing domain name
The recommended way of securing your website is by using  SSL or TLS certificates installed on your website. Most certificate authorities require you have a domain name, although it is possible to use just your instance ipaddress, it is not only discourage but also rquores a long process to achieve it.

Here i will showing steps to achieving it without a custom domain name by using [nip](https://nip.io/) as a DNS and [caddy](https://caddyserver.com/) as a reverse proxy.


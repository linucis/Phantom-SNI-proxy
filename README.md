# phantom
SNI Proxy All in one as a bundle

#LimitNOFILE configuration for nginx service (Recommended)
vi /etc/systemd/system/nginx.service.d/override.conf

[Service]
LimitNOFILE=65536


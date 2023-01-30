# phantom
SNI Proxy

#LimitNOFILE

vi /etc/systemd/system/nginx.service.d/override.conf

[Service]
LimitNOFILE=65536


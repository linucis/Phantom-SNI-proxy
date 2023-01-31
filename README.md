# phantom <br />
SNI Proxy All in one as a bundle <br />

#LimitNOFILE configuration for nginx service (Recommended) <br />
vi /etc/systemd/system/nginx.service.d/override.conf <br />

[Service] <br />
LimitNOFILE=65536 <br />


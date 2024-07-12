In `/opt/services/nginx-certs` create `ssl.crt` & `ssl.key` corresponding to the domain name
Also in `/opt/services/nginx-certs` run the command `openssl dhparam -out dhparams.pem 4096` to generate `dhparams.pem`

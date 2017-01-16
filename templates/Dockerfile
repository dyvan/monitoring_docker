FROM nginx:alpine
COPY htpasswd.users  /etc/nginx/htpasswd.users
COPY prometheus.conf /etc/nginx/conf.d/prometheus.conf
COPY cadvisor.conf /etc/nginx/conf.d/cadvisor.conf
COPY alertmanager.conf /etc/nginx/conf.d/alertmanager.conf

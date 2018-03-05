
# v0.2.0

FROM haproxy:alpine

RUN mkdir -p /etc/ssl/ca
RUN mkdir -p /etc/ssl/hosts

COPY ./ssl/ca    /etc/ssl/ca
COPY ./ssl/hosts /etc/ssl/hosts

COPY ./haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg

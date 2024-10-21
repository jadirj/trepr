# syntax=docker/dockerfile:1
FROM varnish:7.4

LABEL maintainer="TRE-PR <jadir@tre-pr.jus.br>" \
      org.label-schema.name="trepr-varnish" \
      org.label-schema.description="Treinamento TRE-PR Varnish image." \
      org.label-schema.vendor="TRE-PR"

COPY etc/varnish.vcl /etc/varnish/default.vcl

ARG BUILD_FROM
FROM ${BUILD_FROM}

ENV LANG=C.UTF-8

# Startet Tvheadend mit aktivierter HTTP-Root-Anpassung
CMD [ "tvheadend", "-C", "-u", "root", "-g", "root", "--http_root", "" ]

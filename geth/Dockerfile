ARG VERSION=v1.1.6

FROM dysnix/bsc:${VERSION}
VOLUME ["/.bsc"]
EXPOSE 30311 30311/udp
ENTRYPOINT ["geth", "--port", "30311", "--http.port", "8545", "--ws.port", "8546", "--datadir", "/.bsc"]
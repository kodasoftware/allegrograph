FROM franzinc/agmmr:7.0.0

LABEL Maintainer="Christian Shaw"

ARG agversion=7.0.0
ARG testrelease=

ENV agdistfile=agraph-${agversion}-linuxamd64.64.tar.gz
ENV agversion=${agversion}
ENV agcfgfile=/app/agraph/lib/agraph.cfg
ENV agclusterfile=""

ADD dist/docker-entrypoint.sh /opt
FROM kiwix/kiwix-serve
VOLUME /archive
COPY ./start.sh /usr/local/bin
WORKDIR /archive
ENTRYPOINT ["/usr/local/bin/start.sh"]

FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
RUN apt install sed
ENTRYPOINT ["/entrypoint.sh"]

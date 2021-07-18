FROM debian:9.5-slim

RUN apt install git
ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["sh /entrypoint.sh"]
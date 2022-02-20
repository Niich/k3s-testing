FROM ubuntu

RUN ["apt", "update"]
RUN ["apt", "install", "-y", "netcat"]

EXPOSE 54321

ENTRYPOINT [ "nc" ] 
# CMD ["nc", "-u"]
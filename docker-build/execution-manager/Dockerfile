FROM ubuntu

RUN ["apt", "update"]
RUN ["apt", "install", "-y", "netcat"]

EXPOSE 54321


ENTRYPOINT [ "nc" ] 
# ["nc", "-kluvw", "0"]
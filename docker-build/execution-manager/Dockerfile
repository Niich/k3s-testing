FROM ubuntu

RUN ["apt", "update"]
RUN ["apt", "install", "-y", "netcat"]

EXPOSE 54321

CMD ["nc", "-kluvw", "0",  "54321"]
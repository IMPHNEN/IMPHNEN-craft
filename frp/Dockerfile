FROM ubuntu:latest

WORKDIR /frp

RUN apt update && apt upgrade -y

COPY . .

CMD ["./frpc", "-c", "./frp.ini"]

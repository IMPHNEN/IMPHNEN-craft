FROM ubuntu:latest

WORKDIR /bedrock

RUN apt update && apt upgrade -y
RUN apt install wget curl -y
RUN mkdir /bedrock/worlds 

COPY . .

EXPOSE 19132

CMD ["./bedrock_server"]

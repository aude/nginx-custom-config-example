FROM mcr.microsoft.com/dotnet/core/aspnet:latest

RUN apt update && apt install -y nginx
COPY ./custom.conf /etc/nginx/conf.d/custom.conf

COPY ./init /init
ENTRYPOINT ["/init"]

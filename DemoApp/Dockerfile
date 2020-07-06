FROM mcr.microsoft.com/dotnet/core/aspnet:3.1-buster-slim AS base
RUN ["apt-get", "update"]
RUN ["apt-get", "-y", "install", "vim"]
WORKDIR /app
EXPOSE 80

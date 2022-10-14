# syntax=docker/dockerfile:1
FROM mcr.microsoft.com/dotnet/aspnet:6.0
WORKDIR /app
COPY /app/out .
ENTRYPOINT ["dotnet", "DotNet.Docker.dll"]

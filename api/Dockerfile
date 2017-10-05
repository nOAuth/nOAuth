FROM microsoft/aspnetcore
LABEL name="noauth-api"
ENTRYPOINT ["dotnet", "nOAuth.Api.dll"]
ARG source=.
WORKDIR /app
EXPOSE 80
COPY $source .
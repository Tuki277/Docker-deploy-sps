FROM mcr.microsoft.com/dotnet/aspnet:6.0
ENV ASPNETCORE_URLS=http://+:5000
WORKDIR /app
COPY /publish .
ENTRYPOINT ["dotnet", "BookStoreApi.dll"]
FROM mcr.microsoft.com/dotnet/core/sdk:6.0
WORKDIR /app
COPY . . 
ENV ASPNETCORE_URLS http://*:5155
EXPOSE 5000
ENTRYPOINT ["dotnet", "ExampleMVC.dll"]
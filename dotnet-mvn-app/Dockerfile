FROM mcr.microsoft.com/dotnet/aspnet:7.0

WORKDIR /app

COPY --from=build /app ./

ENTRYPOINT ["dotnet", "mywebapp.dll"]
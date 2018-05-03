FROM microsoft/aspnetcore:2.0
 
WORKDIR /mymvcweb
COPY bin/Release/netcoreapp2.0/publish .
 
ENV ASPNETCORE_URLS http://+:5000
EXPOSE 5000
 
ENTRYPOINT ["dotnet", "mymvcweb.dll"]
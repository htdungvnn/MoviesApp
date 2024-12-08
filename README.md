## Set up DB
[//]: docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=yourPassWord" -p 1433:1433 --name movies-app -d mcr.microsoft.com/azure-sql-edge
docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=htdungM0v13e$" \      ─╯
   -p 1433:1433 --name movies-app --hostname movies-app \
   -d \
   mcr.microsoft.com/mssql/server:2022-latest

Connection String : "MoviesAppDb": "Server=localhost,1433;Database=movies-app;User Id=sa;Password=yourPassWord;TrustServerCertificate=True"
  

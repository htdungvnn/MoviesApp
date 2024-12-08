## Set up DB
docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=yourPassWord" -p 1433:1433 --name movies-app -d mcr.microsoft.com/azure-sql-edge

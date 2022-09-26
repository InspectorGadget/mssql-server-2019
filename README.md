# MSSQL Server 2019 (Docker Compose)

# Usage
1. Clone this repository
2. Run `docker-compose up -d`
3. Connect to `localhost` as host and port as `1433`.
4. Login with `sa` and password `YourPassword` on Azure Data Studio or any SQL Client.
    - Example:
        ![SQL Server Connection](./images/dbeaver.png)
5. You are done. Enjoy!

# Teardown
1. Run `docker-compose down`
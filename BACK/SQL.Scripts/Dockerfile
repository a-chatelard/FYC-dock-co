FROM mcr.microsoft.com/mssql/server:latest

ENV MSSQL_PID Developer
ENV MSSQL_TCP_PORT 1433

RUN (/opt/mssql/bin/sqlservr --accept-eula & ) | grep -q "Service Broker manager has started"
# nodejs-web-api-express-basic-auth-sqlserver

## Description
A POC project for expressjs that uses basic auth.

| username | password |
| -------- | -------- |
| *maria* | *pass* |

## Tech stack
- expressjs
- mssql

## Docker stack
- node:latest
- mcr.microsoft.com/mssql/server:2017-CU17-ubuntu

## To run
`sudo ./install.sh -u`
http://localhost/dogs

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

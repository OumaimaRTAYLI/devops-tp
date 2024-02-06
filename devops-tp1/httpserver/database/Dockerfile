FROM postgres:14.1-alpine

COPY ./db/01-CreateScheme.sql /docker-entrypoint-initdb.d
COPY ./db/02-InsertData.sql /docker-entrypoint-initdb.d 

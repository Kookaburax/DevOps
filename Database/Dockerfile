FROM postgres:14.1-alpine

ENV POSTGRES_DB=db \
   POSTGRES_USER=usr \
   POSTGRES_PASSWORD=pwd

COPY createtable.sql  /docker-entrypoint-initdb.d
COPY insertdata.sql  /docker-entrypoint-initdb.d


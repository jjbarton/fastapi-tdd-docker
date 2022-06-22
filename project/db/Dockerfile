# pull official base image
FROM postgres:14-alpine

# run create.sql on init
# Need to do the following if init doesn't work
# docker-compose down --volumes
ADD create.sql /docker-entrypoint-initdb.d

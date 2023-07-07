# Use a base image for MySQL
FROM mysql:5.7
ENV MYSQL_ROOT_PASSWORD=mohitxenon@
COPY tms.sql /docker-entrypoint-initdb.d/tms.sql
# Expose the port the database listens on (default: 3306)

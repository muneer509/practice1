# expense project MySQL Dockerfile
FROM mysql:8.0
LABEL Owner="Muneer"
LABEL Project="Expense Project"
LABEL Component="MySQL Database"
EXPOSE 3306
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1

ADD scripts/*.sql /docker-entrypoint-initdb.d/



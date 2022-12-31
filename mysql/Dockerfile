FROM mysql:5.7

# COPIA O ARQUIVO PARA DENTRO DE UMA PASTA
# QUE RODA SCRIPTS DE BANCO DE DADOS
COPY schema.sql /docker-entrypoint-initdb.d/

EXPOSE 3306

VOLUME [ "/backup/" ]
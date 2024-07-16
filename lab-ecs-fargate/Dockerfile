# Informando a imagem que vai ser utilizada
# Linux Alpine na ultima versão

FROM alpine:latest

# Instalando o Apache

RUN apk add --no-cache apache2

# Fazendo expose da porta padrão do Apache

EXPOSE 80

# Iniciando o serviço do Apache na execução do container

CMD ["httpd", "-D", "FOREGROUND"]

# COPY ..
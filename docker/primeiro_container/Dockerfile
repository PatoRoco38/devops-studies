FROM nginx:1.19.4-alpine

# Maintainer é o criador da imagem.
LABEL maintainer="Geek university <contato@geekuniversity.com.br>"

# Copia o conteúdo do diretório atual para o diretório padrão do nginx.
# O ponto (.) representa o diretório atual onde o Dockerfile está localizado.
COPY . /usr/share/nginx/html

# Expõe a porta 80 para acesso externo.
EXPOSE 80
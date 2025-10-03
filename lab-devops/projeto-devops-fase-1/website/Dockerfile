# Usa a imagem oficial do Nginx como base
FROM nginx:alpine

# Copia sua configuração personalizada (opcional)
# COPY nginx.conf /etc/nginx/nginx.conf

# Copia os arquivos do seu site para o diretório padrão do Nginx
COPY . /usr/share/nginx/html/

# Expõe a porta 80
EXPOSE 80

# Inicia o Nginx em primeiro plano
CMD ["nginx", "-g", "daemon off;"]
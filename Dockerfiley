# Étape 1 : utiliser l'image officielle NGINX
FROM nginx:latest

# Étape 2 : Copier ton site dans le répertoire du serveur web
COPY . /usr/share/nginx/html

# Étape 3 : Exposer le port 80
EXPOSE 80

# Étape 4 : Lancer NGINX
CMD ["nginx", "-g", "daemon off;"]

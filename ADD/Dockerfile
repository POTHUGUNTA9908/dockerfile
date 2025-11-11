FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html
ADD https://raw.githubusercontent.com/POTHUGUNTA9908/dockerfile/main/Run/dockerfile/index.html /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]
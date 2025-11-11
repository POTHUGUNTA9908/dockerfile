FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html
ADD https://raw.githubusercontent.com/POTHUGUNTA9908/dockerfile/refs/heads/main/Run/dockerfile/index.html
CMD ["nginx", "-g", "daemon off;"]-+
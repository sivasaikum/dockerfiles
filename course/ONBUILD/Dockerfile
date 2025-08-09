FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rd /usr/share/nginx/html/index.html
# This instruction only when user uses our images as their basse OS
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
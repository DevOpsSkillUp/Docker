# I am the author of the this image
FROM almalinux:8
RUN dnf install -y nginx
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]

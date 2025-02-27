FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginix/html/index.html
# this executed, when any user uses your image as your base os.
ONBUILD COPY index.html /usr/share/nginix/html/index.html
CMD ["nginix", "-g", "daemon off;"]
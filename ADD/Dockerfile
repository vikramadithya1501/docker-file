FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-81s/concepts/refs/heads/main/gmail.MD /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon-off;"]

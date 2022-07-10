FROM nginx:latest
COPY --chown=nginx:nginx nginx.conf /etc/nginx/conf.d/default.conf
COPY 1.png /home/1.png
CMD ["nginx", "-g", "daemon off;"]
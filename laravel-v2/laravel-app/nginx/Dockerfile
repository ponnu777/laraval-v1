FROM nginx:1.17-alpine
#COPY  /usr/share/nginx/html

#ADD ./nginx/nginx.conf /etc/nginx/
ADD ./nginx/default.conf /etc/nginx/conf.d/

EXPOSE 9080
CMD ["nginx", "-g", "daemon off;"]

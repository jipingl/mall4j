FROM nginx:1.20
COPY ./dist /usr/share/nginx/html/dist
COPY ./nginx.conf /etc/nginx/conf.d
COPY ./mall-api.xifeng-learn.online.key /usr/share/nginx/cert/mall-api.xifeng-learn.online.key
COPY ./mall-api.xifeng-learn.online.pem /usr/share/nginx/cert/mall-api.xifeng-learn.online.pem

EXPOSE 80 443

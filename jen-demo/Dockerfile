FROM nginx:alpine
ARG ENV_TYPE=local
COPY index.html /usr/share/nginx/html/index.html
RUN sed -i "s/ENV_PLACEHOLDER/$ENV_TYPE/g" /usr/share/nginx/html/index.html
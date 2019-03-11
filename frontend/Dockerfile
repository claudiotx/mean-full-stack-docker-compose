FROM nginx:alpine

ENV NODE_ENV=production
ENV PORT=80

# RUN apk add --update nodejs nodejs-npm \
#     && npm install angular-cli -g -q \
#     && ng build --prod \

COPY nginx/nginx.conf /etc/nginx/nginx.conf

WORKDIR /usr/share/nginx/html

COPY dist/frontend .

EXPOSE $PORT
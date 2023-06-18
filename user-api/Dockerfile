FROM node:16.13.1-alpine3.15
RUN npm i -g npm@8.6.0
RUN addgroup allusers && adduser -S -G allusers user-api
RUN mkdir /home/user-api/.npm && chown -R 1001:1001 /home/user-api/

# FROM node:6.10.3
# LABEL maintainer="Pavan"
# LABEL name=Callbook
# RUN groupadd --gid 1005 user-api && useradd --uid 1005 --gid user-api --create-home user-api
# WORKDIR /home/user-api/app
# COPY . .
# RUN chown -R node:node /home/user-api/
# RUN adduser user-api
# RUN mkdir /home/user-api/.npm && chown -R 1001:1001 /home/user-api/
# USER user-api
# RUN npm install 
# EXPOSE 1004
# ENV MONGO_URL=""
# ENV ADMIN_EMAIL=""
# CMD ["npm","start"]



FROM node:6.10.3
LABEL maintainer="Pavan"
LABEL name=Callbook
RUN adduser --home /home/user-api user-api
RUN addgroup user-api -g 999
RUN mkdir -p /home/user-api/app
USER user-api
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



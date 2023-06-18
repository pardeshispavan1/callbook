FROM node:14
LABEL name=Callbook
RUN mkdir -p /home/node/app/node_modules && chown -R node:node /home/node/app
LABEL maintainer="DeekshithSN"
RUN useradd userapi
WORKDIR /app
COPY . .
RUN npm install 
EXPOSE 1004
USER userapi
ENV MONGO_URL=""
ENV ADMIN_EMAIL=""
CMD ["npm","start"]

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



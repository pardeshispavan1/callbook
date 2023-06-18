FROM node:6.10.3
LABEL maintainer="Pavan"
LABEL name=Callbook
RUN deluser --remove-home node \
  && addgroup -S node -g 999 \
  && adduser -S -G node -u 999 node
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



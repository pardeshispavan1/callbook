FROM node:17.9.0-slim
LABEL maintainer="Pavan"
USER node
ENV NPM_CONFIG_PREFIX=/home/node/.npm-global
ENV PATH=$PATH:/home/node/.npm-global/bin
WORKDIR /home/node
COPY . .
RUN npm install 
EXPOSE 1004
ENV MONGO_URL=""
ENV ADMIN_EMAIL=""
CMD ["npm","start"]

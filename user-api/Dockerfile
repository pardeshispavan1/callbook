FROM node:17.9.0-slim
LABEL maintainer="Pavan"
RUN mkdir -p /home/user-api/app && chown -R node:node /home/user-api/app
WORKDIR /home/user-api/app
COPY --chown=user-api:user-api . .
USER user-api
RUN npm install 
EXPOSE 1004
ENV MONGO_URL=""
ENV ADMIN_EMAIL=""
CMD ["npm","start"]



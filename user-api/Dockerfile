FROM node:17.9.0-slim
LABEL maintainer="Pavan"
RUN useradd userapi
WORKDIR /app
RUN chown -R userapi:userapi /app
RUN chmod -R 777 /app
RUN chmod -R 777 /home/node
COPY . .
RUN npm install 
EXPOSE 1004
USER userapi
ENV MONGO_URL=""
ENV ADMIN_EMAIL=""
CMD ["npm","start"]

FROM node:17.9.0-slim
LABEL maintainer="Pavan"
RUN useradd adminui
WORKDIR /app
RUN chown adminui /app
COPY . .
RUN npm install
EXPOSE 3000
USER adminui
CMD ["npm","start"]
FROM node:18-alpine
LABEL maintainer="Pavan"
# RUN useradd adminapi
WORKDIR /app
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install
COPY . .
EXPOSE 1004
ENV MONGO_URL=""
CMD ["npm","start"]
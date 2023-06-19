FROM node:18-alpine
LABEL maintainer="Pavan"
WORKDIR /app
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm","start"]
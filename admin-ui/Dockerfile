FROM node:18-alpine
LABEL maintainer="Pavan"
WORKDIR /app
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install
COPY . .
ENV REACT_APP_API_URL=""
EXPOSE 3000
CMD ["npm","start"]
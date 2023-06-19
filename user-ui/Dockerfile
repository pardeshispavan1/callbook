FROM node:18-alpine
LABEL maintainer="Pavan"
WORKDIR /app
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install 
COPY . .
EXPOSE 3000
ENV REACT_APP_API_URL=""
CMD ["npm","start"]
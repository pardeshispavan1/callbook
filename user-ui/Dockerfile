FROM node:17.9.0-slim
LABEL maintainer="Pavan"
RUN useradd userui
WORKDIR /app
# RUN chown userui /app
COPY . .
# ENV REACT_APP_API_URL=""
RUN npm install 
EXPOSE 3000
# USER userui
CMD ["npm","start"]

# FROM node:18-alpine
# LABEL maintainer="Pavan"
# WORKDIR /app
# COPY ["package.json", "package-lock.json*", "./"]
# RUN npm install 
# COPY . .
# ENV REACT_APP_API_URL=""
# EXPOSE 3000
# CMD ["npm","start"]
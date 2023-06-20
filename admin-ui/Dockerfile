FROM node:17.9.0-slim
LABEL maintainer="Pavan"
RUN useradd userui
WORKDIR /app
RUN chown userui /app
COPY . .
RUN npm install
ENV REACT_APP_API_URL=""
EXPOSE 3000
USER userui
CMD ["npm","start"]
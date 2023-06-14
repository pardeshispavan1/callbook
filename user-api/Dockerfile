FROM node:14.16.0-alpine3.13
LABEL maintainer="Pavan"
RUN addgroup app && adduser -S -G app app
RUN mkdir -p /app && chown -R app:app /app
USER app
WORKDIR /app
RUN npm install
COPY . .
EXPOSE 1004
ENV MONGO_URL=""
ENV ADMIN_EMAIL=""
CMD ["npm", "start"]
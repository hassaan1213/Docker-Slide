FROM alpine
LABEL maintainer="hassaan.umar1213@gmail.com"
RUN apk add --update nodejs nodejs-npm
COPY . /src
WORKDIR /src
RUN npm install
ENV CREATEDBY="Hassaan Umar"
EXPOSE 8080
ENTRYPOINT ["node", "./app.js"]

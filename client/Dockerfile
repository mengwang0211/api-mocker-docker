FROM daocloud.io/node:10.15.2-stretch
WORKDIR /app
COPY . /app/
EXPOSE 8080
RUN  cd client && npm install
ENTRYPOINT ["npm","run","dev"]




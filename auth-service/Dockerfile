FROM node:latest
WORKDIR /service
COPY . .
RUN npm install
CMD ["npm","start"]
EXPOSE 4002
ENV PORT_ONE=4002
ENV MONGO_HOST=mongo

FROM node:latest
WORKDIR /service
COPY . .
RUN npm install
CMD ["npm","start"]
EXPOSE 4000
ENV PORT_ONE=4000
ENV MONGO_HOST=mongo
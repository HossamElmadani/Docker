FROM node:latest
WORKDIR /service
COPY . .
RUN npm install
CMD ["npm","start"]
EXPOSE 4001
ENV PORT_ONE=4001
ENV PRODUCT_API_URL=http://localhost:4000
ENV MONGO_HOST=mongo
FROM node:20
LABEL Owner="Muneer"
LABEL Project="Expense Project"
LABEL Component="Backend API"
ENV Component=backend
ENV DB_HOST="localhost"
EXPOSE 8080
RUN mkdir -p /opt/server
WORKDIR /opt/server
ADD package*.json .
COPY *.js .
RUN npm install
CMD ["node", "index.js"]

# 1. pick a Node 16 image
FROM node:16-alpine
# 2. set a working directory
WORKDIR /app
# 3. declare all the environemnt variables needed
ENV DATABASE_HOST = "database hostname"
ENV DATABASE_PORT =	"database port"
ENV DATABASE_NAME =	"name of the database"
ENV DATABASE_USERNAME =	"username of the database user"
ENV DATABASE_PASSWORD =	"password of the database user"
# 4. copy the app into the work directory
COPY . .
# 5. install all the packages needed for NodeJS
RUN npm install
# 6. expose the port needed
EXPOSE 3000
# 7. start the app
CMD ["node", "src/index.js"]
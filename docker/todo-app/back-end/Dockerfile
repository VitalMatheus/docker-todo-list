FROM node:14-alpine AS todobackend
WORKDIR /app
COPY . .
ADD node_modules.tar.gz /app/
CMD ["npm", "start"]
EXPOSE 3001

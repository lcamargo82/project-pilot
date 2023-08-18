# Use the official Node.js image as base
FROM node:19

RUN npm cache clean --force

# Atualize o npm para a versão 9.8.1
RUN npm install -g npm@9.8.1

# Set the working directory
WORKDIR /app/frontend/react-app

# Copy package.json and package-lock.json
#COPY frontend/react-app/package*.json ./

# Install dependencies
#RUN yarn install

# Expose port
#EXPOSE 3001

# Start the application
#CMD ["yarn", "start"]

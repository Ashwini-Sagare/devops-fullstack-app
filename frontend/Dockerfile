FROM node:14.17.0


# Set the working directory inside the container

WORKDIR /app


# Copy the local package files to the container's workspace

COPY . .


# Install dependencies
RUN npm install


# Command to start the application

CMD ["npm", "start"]

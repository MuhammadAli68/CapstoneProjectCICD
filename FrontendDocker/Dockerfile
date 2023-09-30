# Use an official Node.js image with version 18 as the base image
FROM node:18

# Set the working directory inside the container
WORKDIR /app

# create serverdata directory in app directory
RUN mkdir clientdata

# Clone your remote repository into the container
RUN git clone https://github.com/MuhammadAli68/CapstoneProjectFrontend.git

# Ser the working directory inside the container
WORKDIR /app/CapstoneProjectFrontend

# Expose the port the app runs on
EXPOSE 5000

# Command to run the app
CMD [ "node", "client.js" ]
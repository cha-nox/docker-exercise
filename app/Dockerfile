# Getting latest Node official alpine image
FROM node:23.3-alpine

# Defining the working directory
WORKDIR /app

# Copying the application itself into the container
COPY . .

# Opening the port required by the application
EXPOSE 3000

# Application's health check
HEALTHCHECK --interval=1m --timeout=3s \
    CMD curl -f http://127.0.0.1:3000/ || exit 1

# Defining the running command
CMD ["npm", "run", "start"]
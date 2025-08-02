# Use the official nginx image
FROM nginx:alpine

# Define a build-time argument (with default value)
ARG MY_DUMMY_ARG="default_value"

# Print the ARG value during build
RUN echo "The value of MY_DUMMY_ARG is: $MY_DUMMY_ARG"

# Copy a simple index.html to Nginx web root
COPY index.html /usr/share/nginx/html/index.html

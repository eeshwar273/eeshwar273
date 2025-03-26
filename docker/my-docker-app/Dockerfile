# Use an official Python base image
FROM python:3.9

# Set the working directory in the container
WORKDIR /app

# Copy the current directory content into the container
COPY . /app

# Expose port 8080 to the outside world 
EXPOSE 8080

# Run a simple Python HTTP server
CMD ["python", "-m", "http.server", "8080"]

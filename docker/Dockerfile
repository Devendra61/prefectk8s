# Use an official lightweight Python image as the base image
FROM python:3.11-slim

# Set the working directory in the container
WORKDIR /app

# Create a simple Python script to print a message
RUN echo 'print("Hello, Docker!")' > hello.py

# Define the command to run the Python script
CMD ["python", "hello.py"]
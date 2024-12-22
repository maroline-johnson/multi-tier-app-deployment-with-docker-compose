# Use a lightweight Python image with pip pre-installed
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the API application code to the container
COPY app.py .

# Install Flask (required for the API)
RUN pip install flask

# Expose the port the Flask app runs on
EXPOSE 5000

# Command to run the API
CMD ["python", "app.py"]


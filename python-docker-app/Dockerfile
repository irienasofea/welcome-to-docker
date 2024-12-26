# Use a lightweight Python image
FROM python:3.13.0-slim

# Set the working directory
WORKDIR /app

# Copy the application files to the container
COPY . /app

# Install required Python libraries
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 5000
EXPOSE 5000

# Run the application
CMD ["python", "app.py"]

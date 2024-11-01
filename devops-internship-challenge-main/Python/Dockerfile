# Use Python 3.9 as the base image
FROM python:3.9

# Set the working directory in the container
WORKDIR /app

# Copy app.py to the working directory
COPY app.py /app

# Install required packages
RUN pip install flask netifaces

# Expose port 8000
EXPOSE 8000

# Start the application
CMD ["python", "app.py"]

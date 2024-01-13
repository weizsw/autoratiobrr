# Use an official Python runtime as a parent image
FROM python:3.9-slim

# Set the working directory to /app
WORKDIR /app

# Copy the requirements file into the container at /app
COPY requirements.txt /app/

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Copy the current directory contents into the container at /app
COPY . /app

# Set environment variables
ENV PYTHONUNBUFFERED=1
ENV DRY_RUN=true
ENV SCHEDULE=30

# Run script.py when the container launches
CMD ["python", "-u", "script.py"]
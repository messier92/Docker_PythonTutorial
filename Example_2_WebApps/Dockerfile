# Specify base image
FROM python:3.8

# Absolute or relative path to use as the working directory
WORKDIR /app

# Copy the requirements 
COPY requirements.txt .

# Install the dependencies
RUN pip install -r requirements.txt

# Copy the app folder
COPY ./app ./app

# Run the command line commands 
CMD ["python", "./app/main.py"]



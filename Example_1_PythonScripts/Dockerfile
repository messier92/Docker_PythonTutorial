# Dockerfile is a blueprint for building images
# An image is a template for running containers
# A container is the one running the process

FROM python:3.8

# Add the files to be in the package
ADD main.py . 

# Install dependencies
RUN pip install requests beautifulsoup4

# The command to start when the Docker container is loaded
CMD ["python", "./main.py"]

# The order of the file is important - to build the image, type "docker build -t python-imdb . " in the terminal
#  docker build [OPTIONS] PATH | URL | -
# -t for Name and optionally a tag in the 'name:tag' format
# python-imdb is the name of the application 
# . means to build the file at that location
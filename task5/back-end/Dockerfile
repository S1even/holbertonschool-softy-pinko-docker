# latest ubuntu
FROM ubuntu:latest

# Update APT 
RUN apt-get update

# Upgrade APT
RUN apt-get upgrade -y

# Installs python3 and python3-pip
RUN apt-get install -y python3 python3-pip

# Installs Flask
RUN pip3 install flask

# Installs Flask-Cors
RUN pip3 install flask-cors

# Working directory
WORKDIR /app

# Copies to Working directory
COPY ./api.py /app/api.py

# Port for Flask app
EXPOSE 5252

# Run the Flask app
CMD ["python3", "api.py"]
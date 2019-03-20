Build the image using the following command

$ docker build -t simple-flask-app:latest .

Run the Docker container using the command shown below.

$ docker run -d -p 5000:5000 simple-flask-app

The application will be accessible locally at http:127.0.0.1:5000 or using   the ip address of the image http://<host_ip>:5000

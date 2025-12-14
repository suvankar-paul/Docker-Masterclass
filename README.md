# Docker-Masterclass
This repo is explain how dockers works and how use in for production


Build Docker image:
- docker build -t mlops-docker-demo .

Run the Docker container:
- docker run -p 5000:5000 mlops-docker-demo

Tag the Docker image:
- docker tag mlops-docker-demo vikash95/mlops-docker-demo:latest

Push the image to Docker Hub:
- docker push vikash95/mlops-docker-demo:latest

Pull the image from Docker Hub:
- docker pull vikash95/mlops-docker-demo:latest

Run the pulled image:
- docker run -p 5000:5000 vikash95/mlops-docker-demo:latest

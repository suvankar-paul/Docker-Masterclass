<img width="623" height="332" alt="image" src="https://github.com/user-attachments/assets/9927688b-7b0a-441c-a197-e8296fbdf84f" />



# Docker-Masterclass
This repo is explain how dockers works and how use in for production


Build Docker image:
- docker build -t mlops-docker-demo .

Run the Docker container:
- docker run -p 5000:5000 mlops-docker-demo

Tag the Docker image:
- docker tag mlops-docker-demo suvankar456/mlops-docker-demo:v1

Push the image to Docker Hub:
- docker push suvankar456/mlops-docker-demo:v1

Pull the image from Docker Hub:
- docker pull suvankar456/mlops-docker-demo:v1

Run the pulled image:
- docker run -p 5000:5000 suvankar456/mlops-docker-demo:v1

  complete

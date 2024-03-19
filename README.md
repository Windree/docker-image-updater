# Docker image updater
Update all images referenced in first found docker-compose.yml or docker-compose.yaml 

## Usage
1. Clone this repository into a folder where docker-compose file located
```
git clone https://github.com/Windree/docker-image-updater.git
```
2. Run ./docker-image-updater/update.sh 

3. Restart docker containers
```
docker-compose stop && docker-compose up --build -d
```


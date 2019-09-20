# sonarQube


git clone https://github.com/ricardokanazawa/sonarQube

cd sonarQube

docker run docker/compose:1.14.0 version

docker run --rm -v /var/run/docker.sock:/var/run/docker.sock -v "$PWD:$PWD" -w="$PWD" docker/compose:1.24.0 -f docker-compose-sonarqube.yml up -d



# https://console.cloud.google.com/marketplace/details/google/sonarqube?filter=solution-type%3Ak8s&filter=price%3Afree

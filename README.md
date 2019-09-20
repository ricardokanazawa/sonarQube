# sonarQube


git clone https://github.com/ricardokanazawa/sonarQube
cd sonarQube

docker run docker/compose:1.14.0 version

docker run --rm -v /var/run/docker.sock:/var/run/docker.sock -v "$PWD:$PWD" -w="$PWD" docker/compose:1.24.0 -f docker-compose-sonarqube.yml up

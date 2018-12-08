
#### Build the service image with command

docker build -t murtaza/odin --build-arg JAR_FILE=target/ecsworkshop.service1-1.0-SNAPSHOT.jar .

#### Run the image with command

docker run -p 8080:8080 murtaza/odin


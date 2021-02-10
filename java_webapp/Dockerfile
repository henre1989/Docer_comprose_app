FROM maven:3-openjdk-11
RUN apt update && apt install git -y
WORKDIR /home
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git
RUN mvn package -f /home/boxfuse-sample-java-war-hello/pom.xml
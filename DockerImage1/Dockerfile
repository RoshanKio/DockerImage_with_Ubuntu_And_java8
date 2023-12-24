FROM ubuntu:20.04
COPY Hi.java .
WORKDIR /tmp/
ENV NAME "RAM"
#Running multiple commands
RUN apt-get update && \
	echo "Hello People">file1.txt && \
	echo "Hi Baby">file2.txt && \
	apt-get install -y wget && \
	apt-get install -y openjdk-8-jdk/*
VOLUME ["/myvolume1"]
CMD ["java", "Hi"]
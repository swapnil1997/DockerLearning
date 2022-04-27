FROM openjdk

RUN mkdir -p /home/app

COPY . /home/app

RUN echo $JAVA_HOME

WORKDIR /home/app

RUN javac HelloWorld.java

CMD [ "java", "HelloWorld" ]
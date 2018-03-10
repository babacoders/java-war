
## Pre-requisite:

- Docker 
- Java 

## Cloning the Repository

```
git clone https://github.com/babacoders/java-war
cd java-war
```

## Compiling JAVA  

```
javac HelloWorld.java
```

Note - Please run this from the directory in which you have created your HelloWorld.java, run the command javac HelloWorld.java

## Manifest File

Once you do this, you will get the HelloWorld.class file, which later we will build in .jar. But before that, we need to create a simple manifest.txt to make it packed right.

```
jar cfm HelloWorld.jar manifest.txt HelloWorld.class
```

## verifying

```
java -jar HelloWorld.jar
```

## Building Docker Image

The next step is to start Docker and create a Dockerfile, a text file that contains the instructions (or commands) used to build a Docker image.

```
docker build -t helloworld  
```

## Running the Docker Container 

```
docker run /hello-world
```




# producer-kafka-proj

Download and unzip Kafka on Windows and make sure to setup that properly.  

Run Zookeeper in kafka directory.  

```
.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
```

Run Kafka server using  

```
.\bin\windows\kafka-server-start.bat .\config\server.properties
```

Run this project.

### Output

![image](https://github.com/user-attachments/assets/e36a54b9-b6f8-48ef-a469-84d7322680e2)


Note:

### if any issues while using kafka, try updating this property in server.properties file.  

```
listeners=PLAINTEXT://localhost:9092
```

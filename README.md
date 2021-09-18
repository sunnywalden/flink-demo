## instruction

### pre

edit pom.xml

commentted cotent of groupId org.apache.flink
```
    <scope>provided</scope>
```

### build 

mvn clean package

### run

mvn exec:java -Dexec.mainClass=spendreport.FraudDetectionJob

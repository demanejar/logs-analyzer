# logs-analyzer
parse log

# Run programming
```
sbt clean package
spark-submit --class LogAlalyzerStreaming --master local[2] target/.../...jar
```

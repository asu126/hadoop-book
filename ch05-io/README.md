### run
```
echo "Text" | hadoop jar target/ch05-io-4.0.jar Strer org.apache.hadoop.io.compress.GzipCodec | gunzip
adoop fs -put  /workspace/asu/eclipse-workspace/hadoop-book/ch05-io/src/test/resources/file.gz /user
hadoop jar target/ch05-io-4.0.jar FileDecompressor hdfs://localhost:9000/user/file.gz
```
# apiSampleJava
In order to check instrumentation run these commands:
```
docker build -t example:1 --rm
docker run -d example:1 instrumented_example -p 8080:8080
curl localhost:8080/metrics/prometheus
```

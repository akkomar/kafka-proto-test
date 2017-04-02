

## Update dependencies
```bash
dep ensure -update
```
## Build
```bash
go build -tags static
```
## Run
```bash
./kafka-proto-test BROKER_HOST:9092 CONSUMER_GROUP_NAME TOPIC_NAME

```
## Compile proto schema
```bash
protoc --go_out=. events/AdEvents.proto
```
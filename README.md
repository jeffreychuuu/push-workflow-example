# Push workflow example with Keel and Webhook Relay

## Build image

```
docker build -t docker.io/keelhq/push-workflow-example:latest .
docker push docker.io/keelhq/push-workflow-example:latest
```

To try it locally:

```
docker run -p 8500:8500 keelhq/push-workflow-example
```

## Create Kubernetes deployment

## Reference
https://www.notion.so/Enable-automated-semver-updates-using-Keel-Jeffrey-Version-846fa3fa7da0490b8d7636f0ad3513ba

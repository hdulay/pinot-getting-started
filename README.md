# pinot-getting-started

# Alpine Docker

```bash
git clone https://raw.githubusercontent.com/confluentinc/confluent-kafka-python/

docker build --no-cache \
    -t startree-dev/kafkapy-base:latest \
    -t startree-dev/kafkapy-base:v0.1 \
    -f Dockerfile.alpine .


docker build --no-cache \
    -t startree-dev/kafkapy-producer:latest \
    -t startree-dev/kafkapy-producer:v0.1 \
    -f Dockerfile .
```

## Trouble Shooting

- If you get "No space left on device" when executing docker build.

```docker system prune```


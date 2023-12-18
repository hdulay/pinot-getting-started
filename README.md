# Pinot Getting Started


```mermaid
flowchart LR

Producer-->k[Apache Kafka]-->p[Apache Pinot]
```


```bash
docker compose up -d
```


## Trouble Shooting

- If you get "No space left on device" when executing docker build.

```docker system prune```


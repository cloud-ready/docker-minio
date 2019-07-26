# docker-minio

see: https://hub.docker.com/r/minio/minio

```toml
 [runners.cache]
    Type = "s3"
    Shared = true
    [runners.cache.s3]
      ServerAddress = "host:9000"
      AccessKey = "AccessKey"
      SecretKey = "SecretKey"
      BucketName = "runner"
      Insecure = false
```

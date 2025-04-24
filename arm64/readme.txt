docker buildx create --use --name arm64builder
docker buildx inspect --bootstrap
docker buildx build --platform linux/arm64 -t arm64 .

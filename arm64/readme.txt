sudo apt-get install qemu-user-static -y
docker run --rm --privileged multiarch/qemu-user-static --reset -p yes
docker buildx create --use
docker buildx build --platform linux/arm64 --load -t arm64:latest .

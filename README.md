# qiot-sensor-service-base

Building aarch64 images, using buildx
```shell script
docker buildx build --platform linux/arm64 -t sipsoli/qiot-sensor-service-base-test --push .
```
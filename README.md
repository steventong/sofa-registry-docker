```
docker build . -t tongwanglin/sofa-registry:0.0.1

docker run -p 9615:9615 -p 9622:9622 -p 9603:9603 tongwanglin/sofa-registry:0.0.1
```
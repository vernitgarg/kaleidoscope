To build & push this container navigate to `super-duper-chainsaw/src/` and do:

```
docker build -t [user-id/container-name:tag] -f ../kubernetes/containers/queue-maker/Dockerfile .
docker push [user-id/container-name:tag]
```
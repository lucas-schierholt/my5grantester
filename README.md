# my5grantester


# Docker

```
cd docker
sudo docker buildx build --platform linux/amd64 --push -t maikovisky/my5grantester:main -t maikovisky/my5grantester:latest .
```


# Kuberbnet

```
kubectl apply -f my5grantester.yaml 
```

 

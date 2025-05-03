# deployment-01-starting-setup


### Build image:
```
docker build -t node-img . 
```

### Run the docker:
```
docker run -d --rm -p 80:80 node-img
```
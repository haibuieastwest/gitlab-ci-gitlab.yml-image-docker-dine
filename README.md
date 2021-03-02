# gitlab-ci-gitlab.yml-image-docker-dine
Override gitlab.yml image. This image already set up docker-compose and fully ubuntu needed features

# Build images

```bash
  docker build -t ubuntu-docker-compose .
```

# deploy to docker hub
Run command line as administrator

```bash
  docker login --username=haibuieastwest
  docker tag ubuntu-docker-compose haibuieastwest/ubuntu-docker-compose:latest
  docker push haibuieastwest/ubuntu-docker-compose:latest
```

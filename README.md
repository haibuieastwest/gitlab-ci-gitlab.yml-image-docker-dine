# gitlab-ci-gitlab.yml-image-docker-dine
Override gitlab.yml image. This image already set up docker-compose and fully ubuntu needed features

# Build images

```bash
  docker build -t ubuntu-docker-compose .
```

# deploy to docker hub

```bash
  docker tag ubuntu-docker-compose haibuieastwest/ubuntu-docker-compose:latest
  docker push haibuieastwest/ubuntu-docker-compose:latest
```

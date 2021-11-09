# Workshop Tools

This repository represents the workspace container to run the end-to-end developer workshop.

## Build and Push the image

```
IMAGE_TAG=X
docker build -t quay.io/redhat-emea-ssa-team/workshop-tools:${IMAGE_TAG}
docker push quay.io/redhat-emea-ssa-team/workshop-tools:${IMAGE_TAG}
```
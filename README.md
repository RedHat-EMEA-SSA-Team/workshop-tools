# Wokshop Tools

This repository represents the workspace container to run the end-to-end developer workshop.

## Build and Push the image

```
IMAGE_TAG=X
podman build --layers=false -t quay.io/redhat-emea-ssa-team/workshop-tools:${IMAGE_TAG} .
podman push quay.io/redhat-emea-ssa-team/workshop-tools:${IMAGE_TAG}
```

By default we assume amd64 output and amd64 podman. However for podman running on Mac with Apple Silicon use the extra podman build 
parameter to force this `--platform=linux/amd64`

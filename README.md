# docker-node-circleci

Docker image for circle ci based on circleci/node with some common dependencies.

## How to use

Use the image as usual for CircleCI 2:

```yaml
jobs:
  deploy:
    docker:
      - image: paflopes/node-circleci:6
    steps:
      - checkout
```

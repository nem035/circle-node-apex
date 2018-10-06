# Circle Node Apex Image

Docker image extending [CircleCI Node Image](https://hub.docker.com/r/circleci/node/) and installing [Apex](http://apex.run).


- Building an image

```bash
docker build \
  -t nem035/circle-node-apex \
  --build-arg NODE_VERSION="8.10.0" \
  --label "CircleCI Node 8.10.0 with Apex" \
  .
```

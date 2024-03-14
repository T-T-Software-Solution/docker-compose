## Reference
2024/03/14
https://superset.apache.org/docs/installation/installing-superset-using-docker-compose/


## Command

[Clone Superset's repo](https://github.com/apache/superset) in your terminal with the following command:

```
git clone https://github.com/apache/superset.git
```

### Option #3 - pull and build a release image from docker-hub[](https://superset.apache.org/docs/installation/installing-superset-using-docker-compose/#option-3---pull-and-build-a-release-image-from-docker-hub)

PS. `3.1.0` = Version of the Superset that works properly with dashboard embedded in React

```
export TAG=3.1.0
docker compose -f docker-compose-image-tag.yml up
```
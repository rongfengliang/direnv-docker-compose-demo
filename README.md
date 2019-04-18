# use direnv with docker-compose

just for diffrent env load

## how to running

* for test env

```code
cd test
docker-compose -f ../docker-compose.yaml up -d
```

* for product env

```code

cd prod

docker-compose -f ../docker-compose.yaml up -d

```

* test env value

```code
docker-compose -f ../docker-compose.yaml  exec web sh
env
```
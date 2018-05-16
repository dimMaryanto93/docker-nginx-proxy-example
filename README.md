# docker-nginx-proxy-example

Belajar proxy dengan nginx di docker container,

## how to run it

Build project `registration` & `script`

```bash
cd registration && ng build --prod && cd ../script && ng build --prod
```

Run docker compose

```bash 
docker-compose up
```

## Checklink

- [mits/registration](http://localhost/mits/registration)
- [mits/script](http://localhost/mits/script)
- [proxy to backend](http://localhost/login/oauth/token?grant_type=password&client_id=mandiri_mits&user=user&password=password)

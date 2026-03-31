## Test Config Nginx

docker compose exec nginx nginx -t

## Reload confignya:

docker compose exec nginx nginx -s reload

## Serve static html

localhost:8080

## Test api backend go (bukan di container)

curl http://localhost:8080/api/health

kalau urlnya itu localhost:8080/api/health maka akan diforward ke backend
jadi semua yang setelah "/api/" itu akan diforward ke backend

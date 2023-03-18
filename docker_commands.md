- `docker exec -it <container_name> <command_intepreter>` - подключиться к контейнеру
- `docker compose exec <container_name>`                  - подключиться к контейнеру
-----

- `docker stop $(docker ps -a -q)`           - остановиь все контейнеры
- `docker rm $(docker ps -a -q)`             - удалить все контейнеры
- `docker rmi $(docker images -q)`           - удалить все образы
- `docker volume rm $(docker volume ls -q)`  - удалить все тома
- `docker system prune -a --volumes`         - все команды выше в одной
-----

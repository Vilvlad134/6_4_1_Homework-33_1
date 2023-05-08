## Сборка контейнера
```bash
docker build . --tag=my_api_app
```
*my_api_app* - тэг образа

## Запуск контейнера c пробросом портов
```bash
docker run -d -p 8080:8000 my_api_app
```

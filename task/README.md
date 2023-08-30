### Поднять Django приложение с помощью Docker Compose

1. Скопируйте репозиторий приложения [CRUD: Склады и запасы](https://github.com/kievsan/stocks_products/tree/docker-compose): 
    ```
    git clone --branch docker-compose --single-branch https://github.com/kievsan/stocks_products
    ```
2. Перейдите в директорию проекта stocks_products, затем выполните:
    ```
    docker-compose up --build -d
    ```


# mtrpzLab3

# Простий веб-застосунок на Flask з Docker

Це простий веб-застосунок на Python з використанням фреймворку Flask, який було упаковано у контейнер Docker.

## Як запустити

Для запуску цього веб-застосунку вам знадобиться Docker. Якщо ви ще не встановили Docker, перш ніж продовжувати, встановіть його, використовуючи [офіційні інструкції Docker](https://docs.docker.com/get-docker/).

Після встановлення Docker виконайте наступні кроки:

1. Склонуйте репозиторій з цим кодом:

    ```bash
    git clone https://github.com/aleksandrgarachun/mtrpzLab3
    ```

2. Перейдіть у каталог зі склонованим кодом:

    ```bash
    cd ...
    ```

3. Побудуйте образ Docker:

    ```bash
    docker build -t myflaskapp .
    ```

4. Запустіть контейнер Docker:

    ```bash
    docker run -p 5000:5000 myflaskapp
    ```

5. Тепер ваш веб-застосунок буде доступний за адресою [http://localhost:5000/](http://localhost:5000/).

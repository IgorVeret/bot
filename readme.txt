1.Создайте папку в корне диска. С названием "bot"
2. Скопируйте файлы в эту папку
3. Установите docker, в файле config.py  установите свой TOKEN
4. Запустите команды
docker build -t tg-bot .
docker run -d tg-bot

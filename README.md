# Для запуска контейнера необходимо:

1. Собрать образ:
   <code>docker image build . --tag=dj:1.0</code>
2. Запустить сборку:
   <code>docker run -d -p 8000:8000 dj:1.0</code>
3. Использовать команды для проверки из файла:
   [requests-examples.http](<https://github.com/MaxTols/Docker_2/blob/master/stocks_products/requests-examples.http>)
### Вариант
Задание 22  
Разработать скрипт, который:

1 Запрашивает путь к файлу  
2 Для данного файла выводит построчно временные метки в формате:
- время последнего доступа
- время последнего изменения
- время изменения индексного дескриптора Для выполнения задания используйте команды ls или stat.

### Как работает?
1 Делаем git clone  
2 Собираем образ docker build -t test .  
3 Запускаем контейнер docker run -it CONTAINER_ID   
4 Далее запускается скрипт в режиме диалога, читаем и наслаждаемся (путь файла можно указать ./7171_script_22v.sh)
